# AI Blog App

An application with a Django backend and HTML frontend for generating blog articles from YouTube video transcripts.

## Project structure

- `Frontend/` - standalone HTML pages
- `backend/ai_blog_app/` - Django project, application code, templates, and migrations

The SQLite database, downloaded media, environment files, and the separate `backend/django-netflix-clone/` project are intentionally excluded from this repository.

## Configuration

Set `DJANGO_SECRET_KEY` in your environment before starting Django. Configure the database and the AssemblyAI/OpenAI credentials for your environment; do not commit credentials or local `.env` files.
