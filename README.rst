Cholycy
--------

Since mercari is a selling app, people like to buy or sell something on it. However, there maybe some stuff that cannot sell after a long time, or some people want to do something special instead of selling it, we can provide a port to do something to the social and reduce waste.

"my-proto-blog" is a simple Django app to build a Web-based blog, which aims at calling for people donate their useless stuffs to the people in need. Visitors can view the existing blogs, which about descriptions of donations and stuff lists to the people who are in need. Administrators can edit the exsiting blog and add a new blog.  

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
