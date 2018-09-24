Cholycy
--------

"my-proto-blog" is a simple Django app to build a Web-based blog, which aims at calling for people donate their useless stuffs to the people in need and publish DIY-related tips. Visitors can view the existing blogs, which about descriptions of donations and DIY-related article to help people deal with waste stuff. Administrators can edit the exsiting blog and add a new blog.  

Require
----------
Python version: 3.7
Django version: 2.1

Quick start
-----------
1. Add "blog" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'blog',
    ]

2. Include the blog URLconf in your project urls.py like this::

    path('blog/', include('blog.urls')),

3. Run python manage.py migrate to create the blog models.

4. Start the development server and visit http://127.0.0.1:8000/admin/ to create a blog (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/blog/ to view the blog.
