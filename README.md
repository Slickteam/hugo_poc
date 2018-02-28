# Migration of Slickteam's website to Hugo

The purpose of this project was to migrate the content management of the website from WordPress to Hugo.

I did not spend time on the refactorisation of the frontend code. I just kept it like it was with the WordPress theme.

If you want to see some Hugo mechanisms and play with, you can grab this project as it is just a POC serving as base for his concepts.

## Concepts
Here are some of the concepts I used in this project :

### Custom data
There are some data that are used to generate content on the homepage. You can find this data in the `config.toml` file at the root of the project.

### Custom content
There are two sections which data is retrieved from files in the `content/` directory. You can modify them or add new ones based on these ones.