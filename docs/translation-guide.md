# Translation Guide

## How to Add a New Language

1. **Copy the Portuguese object** (`pt`) in the `I18N` object
2. **Rename the key** to the appropriate language code (e.g., `fr` for French)
3. **Translate all strings** maintaining the same structure
4. **Test thoroughly** in all 3 views (intro, questions, results)
5. **Submit a Pull Request** with screenshots

## Language Detection

The tool automatically detects browser language and falls back to English if not supported.

Supported languages:
- `pt-BR`: Portuguese (Brazil)
- `en-US`: English (US)
- `es-ES`: Spanish (Spain)

## Translation Tips

- Keep technical terms consistent with clinical literature
- Maintain gender-neutral language where possible
- Preserve the emotional tone of questions
- Test for cultural appropriateness
- Ensure accessibility compliance

## Quality Assurance

Before submitting:
- [ ] All strings translated
- [ ] No broken placeholders
- [ ] Consistent terminology
- [ ] Tested in browser
- [ ] Screenshots included