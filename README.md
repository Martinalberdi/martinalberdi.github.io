# Martín Alberdi 

Source for [martinalberdi.github.io](https://martinalberdi.github.io), my academic webiste.

## Local development

Requirements: Ruby 3.2.2 and Bundler.

```sh
bundle install
bundle exec jekyll serve
```

The local preview is available at <http://127.0.0.1:4000/>.

## Validation and deployment

Run the same checks used by continuous integration:

```sh
bundle exec script/cibuild
```

Pushes to `main` are built, validated, and deployed automatically with GitHub Actions.
