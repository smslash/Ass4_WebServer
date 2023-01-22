# Application

Web application to search for news and articles about cryptocurrency.

## Installation

To get started with the application you need to complete following steps:

- Install requirements:

```shell
$ pip install -r requirements.txt
```

- Create `.env` file in root directory of the project and add there `SECRET_KEY` and `DB_URI` variables:

```
SECRET_KEY=your-secret-key
DB_URI=your-database-uri
```

- Create tables in your database:

```sql
CREATE TABLE NEWS(
	id VARCHAR PRIMARY KEY,
	url VARCHAR,
	heading VARCHAR,
	paragraph VARCHAR
)
```

- Run application:

```shell
$ python3 src/app.py
```

## Usage

In order to use the application, input coin name into the textfield, simply click on the search button and after search button is pressed, page should show list of paragraphs.

## Example

<p align="center">
  <img src="https://github.com/ootsutsukee/AdvProPython-assignment-4-web-server-/blob/6e3ba3c3085c1b6d28c97194083383f143c5293c/example.jpg?raw=true" alt="example" />
</p>
