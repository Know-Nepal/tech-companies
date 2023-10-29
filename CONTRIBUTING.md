<h2>Data Format</h2>

All the company data should be in a singular file `companies.json`. Check the `data` folder for example.
The file will be in `.json` and the format of the data will be as follows _(Extra fields may be added later)_;

```json
{
  "companies": [
    {
      "name": "Awesome Company",
      "logoName": "awesomecompany.png",
      "establishedAt": 1667465928,
      "location": "Fully remote",
      "website": "https://anawesomewebsite.com",
      "email": "contact@awesomecompany.com",
      "phone": "+977-012345678",
      "socials": {
        "facebook": "https://facebook.com",
        "instagram": "https://instagram.com",
        "github": "https://github.com",
        "linkedin": "https://linkedin.com",
        "twitter": "https://twitter.com",
        "youtube": "https://youtube.com"
      }
    }
  ]
}
```

<h2>Contributing Guide</h2>

- Always create a relevant branch name.
- Use conventional commits whenever possible.
- Please check the correctness of data before contributing.
- Don't diverge from the format you're provided with.
- The logo for the company should be `128x128` in size and should be placed under `logos/` directory of the repository.

_If you encounter any issues feel free to open an issue or ping us in the [Discord Server](http://discord.gg/7jwZaa8WDr)._
