# {{ cookiecutter.presentation_title }}
{% if cookiecutter.presentation_subtitle %}## {{ cookiecutter.presentation_subtitle }}{% endif %}

{% if cookiecutter.presentation_description %}{{ cookiecutter.presentation_description }}{% endif %}

## Launch the presentation offline

To start the presentation offline using Gitpitch Desktop:

```
$ docker login
$ docker-compose up -d
```

The presentation can then to viewed from [http://localhost:9000](http://localhost:9000)