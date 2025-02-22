---
title: Mejores prácticas para abandonar la empresa
intro: 'If you use your account on {% data variables.product.product_name %} for both personal and work purposes, there are a few things to keep in mind when you leave your company or organization.'
redirect_from:
  - /articles/best-practices-for-leaving-your-company
  - /github/setting-up-and-managing-your-github-user-account/best-practices-for-leaving-your-company
  - /github/setting-up-and-managing-your-github-user-account/managing-user-account-settings/best-practices-for-leaving-your-company
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Accounts
shortTitle: Dejar tu compañía
---

Before you leave your company, make sure you update the following information in your personal account:

- Quitar la marca de verificación de la dirección de correo electrónico de la empresa al [eliminarla de los parámetros de Correo electrónico](/articles/changing-your-primary-email-address). Puedes volver a agregarla sin verificar para conservar todas las confirmaciones asociadas vinculadas con tu cuenta.
- [Cambiar tu dirección principal de correo electrónico](/articles/changing-your-primary-email-address) del correo electrónico de tu empresa a tu correo electrónico personal.
{% ifversion fpt or ghec %}
- [Verificar tu nueva dirección principal de correo electrónico](/articles/verifying-your-email-address).
{% endif %}
- [Cambiar tu nombre de usuario de GitHub](/articles/changing-your-github-username) para eliminar cualquier referencia a tu empresa u organización, si es necesario.

## Abandonar las organizaciones

Si has estado trabajando con repositorios que pertenecen a una organización, deberás [eliminarte como miembro de la organización](/articles/removing-yourself-from-an-organization). Ten en cuenta que si eres el propietario de la organización, primero deberías [transferir tu pertenencia a la organización](/articles/transferring-organization-ownership) a otra persona.

## Eliminar asociaciones profesionales con repositorios personales.

If you've been collaborating professionally with another person on repositories that belong to their personal account, you'll want to [remove yourself as a collaborator](/articles/removing-yourself-from-a-collaborator-s-repository) from those repositories.

- [Deja de mirar repositorios](https://github.com/watching) relacionados con tu trabajo. No desearás volver a ver esas notificaciones.
- [Transfiere los repositorios que posees](/articles/how-to-transfer-a-repository) a otros que deben seguir trabajando con ellos una vez que te marches.
- [Elimina bifurcaciones que te pertenecen](/articles/deleting-a-repository) y que están relacionadas con el trabajo que estabas haciendo. No te preocupes, si eliminas una bifurcación no eliminarás el repositorio ascendente.
- Elimina copias locales de las bifurcaciones que pueden existir en tu computadora.

```shell
$ rm -rf <em>work_directory</em>
```
