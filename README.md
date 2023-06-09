## This repo contains 4 projects described in Django 4 by Example, author Antonio Mele

# Mysite (Chapters 1 - 3)
This is a simple blog site where people can post their articles.
It contains next features:
- Recommendation system via e-mail
- Comment system
- Markdown syntax for articles
- RSS
- Full-text search via PostgreSQL

# Bookmarks (Chapters 4 - 7)
The simple social network where people can pin liked pictures, (seems like Pinterest).
It contains next features:
- Social auth via Facebook, Twitter, Google OAuth
- JavaScript bookmark that is using to find pictures on a page at different sites and then pin them onto own site
- Following system
- Redis is used for counting views

# Myshop (Chapters 8 - 11)
The little shop with a cart, a recommendation system based on added products, and a payment mechanism via Stripe payment gateway.
It contains next features:
- Cart system via session 
- Celery and RabbitMQ are used for managing order creation
- Stripe payment gateway 
- PDF invoice generating
- Discount system
- Recommendation mechanism
- Internationalization, support EN and UA languages

# Educa (Chapters 12 - 17)
This is the simplest remote education platform where Instructors can add their courses and Students can enroll.
It contains next features:
- Creating courses with modules
- Drag-and-drop mechanism to edit the order of modules
- Caching via Redis
- REST APIs via Django-REST-Framework
- Chat system throughout WebSocket via Channels
- Packing apps, uWSGI, Daphne, Redis, PostgreSQL, and NGINX to container via Docker