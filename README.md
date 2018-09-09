# Cholycy

my-proto-blog is a simple Django app to edit Web-based blog, which aims at calling for people donate their useless stuffs to the people in need. Visitors can choose to view exsiting blog or add a new blog.

Quick start
Add "blog" to your INSTALLED_APPS setting like this:

INSTALLED_APPS = [
    ...
    'blog',
]
Include the blog URLconf in your project urls.py like this:

path('blog/', include('blog.urls')),
Run python manage.py migrate to create the blog models.

Start the development server and visit http://127.0.0.1:8000/admin/ to create a blog (you'll need the Admin app enabled).

Visit http://127.0.0.1:8000/blog/ to view the blog.