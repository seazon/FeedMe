# AI Support

FeedMe's AI features can be used for translation and summarization.

### What AI Can Do

| Feature | Where to use | Requires feed switch | Requires purchase to unlock |
| --- | --- | --- | --- |
| Translate title | Article list | Yes, enable `Translate article title when reading` for the feed/category | No |
| Translate full text | Article page menu | No | Yes |
| Summarize a single article | Article page | After enabling `Show AI Summary` for the feed/category, the article page summarizes automatically. Even if not enabled, the article page provides a button to summarize manually. | No |
| Summarize multiple articles in the article list | Article list menu | No | Yes |

#### Translate Title

After completing the setup and enabling `Translate article title when reading` for the feed or category, on the `Article List` page the title will automatically display the translation result after the original title. Articles with an empty title are not translated, and already translated results are saved so they are not translated again.

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/ai_translate_for_list.png" width="25%" height="25%" />

#### Translate Full Text

On an article page, use the translation button in the menu to switch between the translation and the original text; the whole body text will be translated. Tap it again to switch back to the original. This feature does not depend on the `Translate article title when reading` switch, so it can be used anytime.

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/ai_translate_for_article_1.png" width="25%" height="25%" />

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/ai_translate_for_article_2.png" width="25%" height="25%" />

#### Summarize a Single Article

On an article page, the AI-generated summary is displayed at the top of the article body to help you quickly grasp the core of the article. The summary streams out to reduce waiting time, and once generated it is saved, so reopening the same article will not call AI again. Articles with too little content will automatically hide the summary section. After enabling `Show AI Summary` for the feed or category, entering the article page will summarize automatically. But even if not enabled, the article page provides a button to summarize manually.

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/ai_summary_for_article.png" width="25%" height="25%" />

#### Summarize Multiple Articles in the Article List

On the `Article List` page, use `AI Summary` in the menu to create one overall summary of multiple articles in the current list. For easier reading, the result is merged and organized by topic.

The summary page has two buttons: the first marks the summarized articles as read, the second copies the summary content.

Since a single request can only handle a limited number of articles, when the list contains more articles than the limit, only the first ones are summarized; a message is displayed when triggered telling you the article limit for this request. This feature uses a built-in prompt and is not affected by the custom content in `Prompt`.

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/ai_summary_for_article_list_1.png" width="25%" height="25%" />

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/ai_summary_for_article_list_2.png" width="25%" height="25%" />

### Configure AI

Find `AI` in `Settings` - `Service`

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/ai_choose_mode.png" width="25%" height="25%" />

There are two AI types to choose from, and only one is used at any time:

- `Cloud API`: The most capable, requires a network connection.
- `Local Model`: A user-managed offline engine, requires downloading model files larger than 2GB.

After choosing one, you can use the test button below to verify that it works.

#### Cloud API

Set the type, URL, model and key

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/ai_cloud_api_setting.png" width="25%" height="25%" />

- `Type`: Supports Gemini, Volces (Volcano Ark), GLM, QWen, OpenAI, MiniMax, and `Custom`. The `Custom` type requires purchase to unlock.
- `URL`: Normally no change is needed, it is filled in automatically after selecting the type. It can be edited manually when `Custom` is selected.
- `Model`: Select from the dropdown list, or fill it in manually.
- `Key`: The API Key of the corresponding service.

Tap `Save` when done, then use the test button; once it passes, AI is ready to use.

#### Local Model

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/ai_model_local_model.png" width="25%" height="25%" />

With `Local Model` selected, AI runs inference directly on your device with no network connection required. This protects your data privacy and lets you still use summarization and translation while offline.

Models need to be prepared in advance and imported through the `Local Model` dialog:

- Model files must be obtained by yourself — **the app does not provide model downloads**. You can put them on the device using a file manager or adb.
- Tap `Import local model (.litertlm / .task)` and pick the file in the system file picker to start importing; progress is displayed during the import. Model files are usually larger than 2GB, so importing takes a while.
- Imported models are stored in the app's private directory and can be deleted at any time.

After importing, a model can be configured as follows:

- `Set as default`: Use it as the current local model.
- `Speed test`: Test how fast the model runs on this device; the result is shown in tokens per second, giving you a rough idea of the model's speed on your device.
- `Backend`: Choose GPU, CPU or Auto for each model individually.

### Custom Prompt

Find `Prompt` in `Settings` - `Service` to customize the prompt for the two scenarios: `Summary` and `Translation`.

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/ai_prompt_setting.png" width="25%" height="25%" />

Follow these rules when writing prompts:

- Use the `{content}` placeholder to represent the content of the article.
- Use the `{language}` placeholder to represent the target language of the AI-generated content (configurable in the language setting).

Both placeholders must be present; missing either one will prevent saving. You can restore the default prompt at any time.

Scope:

- The `Translation` prompt is used for both `Translate title` and `Translate full text`.
- The `Summary` prompt is used for `Summarize a single article`.
- `Summarize multiple articles in the article list` uses a built-in prompt and is not affected by the settings here.

Custom prompts require purchase to unlock.

### Enable AI for Feeds / Categories

`Translate title` and `Summarize a single article` need to be enabled separately for each feed or category.

On the `Subscriptions` page, open a page of a feed or category, find `Translate article title when reading` or `Show AI Summary`, and enable it

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/ai_setting_in_feed_setting.png" width="25%" height="25%" />

Each switch has three states: follow parent, no, yes. A feed can inherit the settings of its category, and a category can inherit the global settings, so you can enable translation only for the foreign-language feeds you need instead of turning it on everywhere.

`Translate full text` and `Summarize multiple articles in the article list` do not need to be enabled here; use them directly once AI is configured.

### Purchase to Unlock

| Item | Requires purchase to unlock |
| --- | --- |
| Translate title | No |
| Summarize a single article | No |
| Select `Local Model` as the AI type | No |
| Translate full text | Yes |
| Summarize multiple articles in the article list | Yes |
| Custom prompt | Yes |
| Use the `Custom` type in Cloud API | Yes |

Using a paid feature while it is locked will take you to the in-app purchase page. The AI configuration itself has no extra cost; the actual cost depends on the pricing of the Cloud API service you choose.
