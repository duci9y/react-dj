# react-dj

A template to develop React single-page applications (SPAs) with a
Django REST Framework backend with support for simple deployments to Heroku.

## Setup instructions

1.  Clone this repository. `git clone https://github.com/duci9y/react-dj.git` in your shell or
    your favorite Git client. I recommend [Sourcetree](https://www.sourcetreeapp.com).

2.  Install Python dependencies. `pipenv install`.

3.  Install JavaScript dependencies. `yarn install`.

4.  Start your [virtual environment](https://www.google.com/search?q=virtual+environment+python) shell:
    `pipenv shell`.

5.  Start the Django development server. `./server/manage.py runserver`.

6.  Open a new tab/window in your terminal, with the repository root as your working directory.
    Start the frontend development server in this tab: `yarn start`.

7.  The previous step should have opened [http://127.0.0.1:3000](http://127.0.0.1:3000) in a browser
    window. If not, you can click on the link above.
