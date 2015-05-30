# CocoaPods State of the Union

Web service to manage the CocoaPods State of the Union lottery.

## Environment

SOTU expects the following environment variables configured:

- `DATABASE_URL`
- `GITHUB_CLIENT_ID`
- `GITHUB_CLIENT_SECRET`

## Setup

1. Create a virtual environment:

        $ virtualenv venv

2. Activate the virtual environment:

        $ source venv/bin/activate

3. Install the dependencies:

        $ pip install -r requirements.txt

4. Migrating the database:

        $ invoke migrate

## Running the website

You can use [foreman](https://github.com/ddollar/foreman) to run the server.

```shell
$ foreman start
```

