# User Authentication Service

This project implements a user authentication service using Flask and SQLAlchemy.

## User Model

The `User` model represents a user in the authentication system. It includes the following attributes:

- `id`: The integer primary key.
- `email`: A non-nullable string.
- `hashed_password`: A non-nullable string.
- `session_id`: A nullable string.
- `reset_token`: A nullable string.

## Setup

### Prerequisites

- Python 3.7
- Pip
- SQLAlchemy 1.3.x
- bcrypt

### Installation

```bash
sudo apt update
sudo apt install python3 python3-pip
pip3 install bcrypt sqlalchemy

