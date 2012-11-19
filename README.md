makefile do Drupal Brasil
=========================

Make file para a instalação do Drupal Brasil

**ATENÇÃO**: Os trabalhos para a reestruturação do Drupal Brasil serão concentrados no repositório **https://github.com/drupal-br/drupalbr-d7**. Este repositório será mantido apenas enquanto estamos migrando as features.

Instruções
----------

```sh
drush make drupal_brasil_d7.make dbr
cd dbr
drush si --db-url=mysql://root:@localhost/dbr7 --account-name=admin --account-pass=admin --account-mail=contato@example.com --site-name="Drupal Brasil DEV" --site-mail="contato@example.com"
drush en dbr_defaults
drush en dbr_groups dbr_discussions dbr_events dbr_articles dbr_polls dbr_jobs dbr_showcase dbr_profile
```