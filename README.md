# City Game Studio translations

A repository for City Game Studio's translation efforts. There is only one folder:

- **languages** contains a list of files for every supported languages

## Contributing languages

A language is just a yaml file that maps phrases in English to phrases in another
language. Here's a small example:

```yaml
# Comments start with an octothorpe
# Write whatever notes are necessary in a comment

# Here's a mapping of a hypothetical City Game Studio phrase:

TOOLTIP_RECRUIT: List potential candidates available in town
```

Mappings will appear as:

```yaml
IDENTIFIER: [Phrase printed according to language options]
```

When translating languages type the translated phrase below the English phrase.
Here is an example of a hypothetical Spanish translation:

```yaml
TOOLTIP_RECRUIT: Lista de posibles candidatos disponibles en la ciudad.
```

Sometime a phrase might contain a parameter. It is always `%s`.

```yaml
# First %s matches the manufacturer of the platform
# Second %s matches the platform's name
LABEL_PLATFORM_RELEASED_DESCRIPTION: "%s has released a new platform: '%s'"
```

To print a single `%` we need to double it: `%%`.

```yaml
LABEL_LOAN_DESCRIPTION: >
    You need some extra money, we can help you. You can refund yourself with a loan of %s$.
    Our interests rates are as low as only %s%%, and you have %s weeks to repay.
    Its like a whole life for a company like yours. We are your last option, let yourself be tempted.
```
All languages files should be named `[language].yaml`.

## Contact

If you have questions about contributing [contact us](https://www.binogure-studio.com)
or send an email to contact@binogure-studio.com.
