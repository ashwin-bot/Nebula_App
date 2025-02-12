<h1 align="center" id="title">Nebula</h1>

<p align="center"><img src="https://socialify.git.ci/ashwin-bot/Nebula_App/image?description=1&amp;font=Source+Code+Pro&amp;language=1&amp;name=1&amp;owner=1&amp;pattern=Signal&amp;stargazers=1&amp;theme=Auto" alt="project-image"></p>

<p id="description">Real-time web chat application using Flask-SocketIO and WebSocket. A scalable server infrastructure that can handle concurrent connections ensuring smooth and efficient communication for all users.</p>

## Project Structure

```
Chat_Web_App/
    Images/
        icon.jpg
    insctance/
        database.db
    Myapp/
        __pycache__/
        static/
            images/
            auth.css
            chat.css
            index.js
            styles.css
        templates/
            auth.html
            base.html
            chat.html
            visualize.html
        __init__.py
        config.py
        database.py
        views.py
    README.md
    requirements.txt
    .env
    server.py
```

## Project Architecture
### `__init__.py`

Initialization of the Flask application, configuration, and extension setup.

### `config.py`

Configuration settings for the Flask application, including the secret key and database URI.

### `database.py`

Database models and schema definition using SQLAlchemy. Includes user, chat, and message models.

### `views.py`

Blueprint for route views, including login, registration and chat.

### `server.py`

Entry point for running the server. Initializes the Flask application and Socket.IO communication events.

![alt text](http://url/to/img.png)

## Key Features 
- Secure User Authentication: Users can register and log in securely with password hashing to protect credentials.
- Real-time Messaging: Instant chat updates in individual chat rooms without refreshing the page.
- Dynamic Chat List: Automatically updates the chat list with new messages and active users.
- Message History: Stores chat history so users can view previous conversations.

  
