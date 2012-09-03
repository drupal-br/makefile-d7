makefile do Drupal Brasil
=========================

Make file para a instalação do Drupal Brasil

Instruções
----------

```sh
drush make drupal_brasil_d7.make dbr
cd dbr
drush si --db-url=mysql://root:@localhost/dbr7 --account-name=admin --account-pass=admin --account-mail=contato@example.com --site-name="Drupal Brasil DEV" --site-mail="contato@eusouopedro.com"
drush en dbr_defaults
drush en dbr_groups dbr_discussions dbr_events dbr_articles dbr_polls dbr_jobs dbr_showcase dbr_profile
```