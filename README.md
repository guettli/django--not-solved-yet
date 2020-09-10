# The Django Webframework is great. But some things are not solved yet

This page is me doing brainstorming in an open and public fashion. Feedback is welcome.

# Row based permissions

You can use [Gardian](https://django-guardian.readthedocs.io/en/stable/) which is slow.

You can overwrite [ModelAdmin.get_queryset()](https://docs.djangoproject.com/en/3.1/ref/contrib/admin/#django.contrib.admin.ModelAdmin.get_queryset) in the Django admin.

You can use [User.has_perm()](https://docs.djangoproject.com/en/3.1/ref/contrib/auth/#django.contrib.auth.models.User.has_perm) but the implementation is up to you.

Related: [Do permission checking via SQL](https://github.com/guettli/programming-guidelines#do-permission-checking-via-sql)

# Install Plugins via Web-GUI

This would be great.

# Add custom columns

Imagine you have created some kind of commercial issue tracking software. You have 20 customers.

One customer wants to extend the application. He wants to add some special columns which are not needed
by the other 19 customers.

How to solve this?

[EAV](https://en.wikipedia.org/wiki/Entity%E2%80%93attribute%E2%80%93value_model) is one solution

# Simple open source CMS based on Django

There is DjangoCMS and Wagtail. But both are too heavy for me. It would be cool to have a really lightweight CMS app for Django.

