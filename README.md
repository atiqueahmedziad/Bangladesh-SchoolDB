Bangladesh School Database
=====================================
A collections of basic details about schools in Bangladesh.

## Disclaimer
Most information in this repository was scraped from websites some of which may be potentially unmaintained. Relying solely on this the information for tasks of high significance is not encouraged.

This collection is no where near complete and possibly never will be, but I/we'll do our best to add all that we can and keep the information updated.

## Contributing
1. Fork the Repository
2. Append another entry at the end of the JSON Array
3. Send me a pull request

Alternatively you could
1. Create an Issue with all the impormation about the school(s) you want added
2. Email me at [o.jamal97@gmail.com](mailto: o.jamal97@gmail.com) with the details.

### Structure
The data is in JSON Format consisting of one big array of objects. Each object contains details about a school.

Example entry
```json
[
    .....
    {
        "name": "Cardiff International School Dhaka",
        "alternate_name": "CISD",
        "addresses": [
            "House # 60/A, Road # 27 (old), 16 New, Dhanmondi, Dhaka-1209",
            ....
        ],
        "phones": [
            "9125289",
            ....
        ],
        "emails": [
            "info@cisdbd.org",
            ....
        ],
        "website": "http://www.cisdbd.org/",
        "curriculum": "international"
    },
    .....
]
```

### Details Stored
- **Name** (`name`) - Full, Formal Name of the School.
- **Alternate Name** (`alternate_name`) - Shorter or more popular version of the name. _optional_
- **Addresses** (`addresses`) - Array of Addresses
- **Phones** (`phones`) - Array of phone Numbers
- **Emails** (`emails`) - Array of Email Addresses
- **Website** (`website`) - The Web address of the official website of a school. _Optional but highly recommended_
- **Curriculum** (`curriculum`)

## License
### Public Domain (Unlicense)
You can really do anything you want to with this data. Except hold me/us the contributor(s) liable for any damages 'caused.

For more info read: [LICENSE](LICENSE)
or read it on TL;DR Legal: [Unlicense](https://tldrlegal.com/license/unlicense)
