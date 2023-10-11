# Portfolio with Drupal 10

> Not for the faint of heart

A low-code approach creating a portfolio site with Drupal 10.

## Built with

- Drupal 10
- Lando ♥️

### Key Modules

- Pathauto
- Paragraphs
- Layout Paragraphs
- Layout Builder (used for Contact page for experiment purposes)

### Theme

- [Power Portfolio Theme](https://www.drupal.org/project/power_portfolio)

This theme is not without its issues and I would recommend a more stabler one but it has some nice looking css and js features out of the box. Use at your own caution.

## Setup and Usage

Clone repo
```bash
git clone https://github.com/julilan/drupal10_portfolio.git
```

Try these commands
```bash
lando composer install
lando db-import drupal10.2023-10-11-1697044717.sql.gz --no-wipe
lando drush cim
lando start
```

Good luck 🦔

Hack your way inside in case the site is broken 👻
```bash
lando drush upwd admin admin
```

- Go to {address_of_your_choosing}/user/login
- Go to Appearance -> Power Portfolio Settings -> Banner Config. -> Upload a bg image

## Live Site

This site will not be hosted in the near future or ever. Drupal is a bit too weighty for a portfolio site in general. But it has its uses for example if you want to incorporate blog posts and articles to your portfolio then Drupal starts to shine with its capabilities with content management.

## Screenshot

![drupal_portfolio_screenshot](https://github.com/julilan/drupal10_portfolio/assets/122397061/6e3ded67-dc91-4089-b3ba-5bbe1dd02fc3)

## Author & Acknowledgements

Julianna Molnár [@julilan](https://github.com/julilan)

Thank you to fellow course mates of REACT23K group of Business College Helsinki and our teacher [@kalwar](https://github.com/kalwar) for sharing this introductory journey into Drupal.

## Closing image

![drupal_love_or_hate](https://github.com/julilan/drupal10_portfolio/assets/122397061/43212134-1a87-4d01-ae0d-79c211a1cf6a)
