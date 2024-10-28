## JpQuest

Translator for FTBQuest. (title, subtitle, description)  
If you want to translate to other languages than Japanese,  
please add the `language` option during initialization.  
Can always get help with `JpQuest.help`

#### Example

`JpQuest::SNBT::Performer.new(language: "English")`  
or if no specific configs required  
`JpQuest.omakase(language: "English")`

## Steps

1. Download [release](https://github.com/milkeclair/jp_quest/releases)
2. Make `.env` file
3. Add `OPENAI_API_KEY=your_api_key` to `.env`
4. Optional: Add `OPENAI_MODEL=some_openai_model` to `.env` **(default: gpt-4o-mini)**
5. Add `some.snbt` or `quests` directory contents to `quests` directory
6. Check `output` directory

## Initialize Options

#### output_logs

Want to output OpenAI usage logs?
**(default: true)**

#### except_words

Words that you don't want to translate
**(default: empty array)**

#### language

Which language do you want to translate to?
**(default: Japanese)**

#### display_help

Want to display help?
**(default: true)**
