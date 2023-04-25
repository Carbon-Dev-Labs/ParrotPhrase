
<a href="https://parrotphrase.carbondev.cf">
    <img alt="ParrotPhrase" src="https://parrotphrase.carbondev.cf/assets/images/logo/ParrotPhraseLogoWhite.png" width="100" />
</a>

# Parrot Phrase

A text pharaphrasing tool to help make your writing sound more natural

## Notice

**Parrot Phrase is not released yet** because the project has just been started. We plan to work on it throughout the following months untill we get a public beta.

## Roadmap

- A working paraphrasing tool.

- Working text editor.

## API Reference

```https
  https://parrotservice.carboncdn.cf
```

### Paraphraser example

```https
  POST /api/paraphraser
```

```json
  'Content-type': 'application/x-www-form-urlencoded'
```

> You have to use the urlencoded form headers otherwise your request will be denied.

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `input` | `string` | **Required**. The text to paraphrase |
| `tone` | `string` | The type of tone to use when writing |
| `useai` | `boolean` | Should the paraphraser use AI to write |

### API Limits

Due to this being a free service, there are going to be some limits. There is no paid teir service or anything like such yet and there might not be. We don't know where Parrot might go so bear with us.

- 20 request per hour
- 3,000 word requests only

## FAQ

#### When will Parrot Phrase be avliable for use?

Sometime in the next 4 months. We are working on getting a basic AI system setup and trained to rephrased text to make the tone seem more natural.
## Authors

- [@CleverCarpet](https://www.github.com/clevercarpet)


## License

[MIT](https://choosealicense.com/licenses/mit/)

