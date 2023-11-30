# Upload Documentation 

First of all you have to upload all your documentation to GitHub.
Once you have it done come [here](https://about.readthedocs.com/?ref=readthedocs.com) and create an account on ReadTheDocs page.

When you are signed up you have to click on "import a project" button from your dashboard

Here we click on Connect to GitHub 

We log in on GitHub if its necessary or just give ReadTheDocs permission to access our repositories (Note: The repository must be public if you want to use the free version of the tool). 

Then we select our repository and follow the instructions to deploy the Documentation page.

It will ask us to create a .readthedocs.yaml file. On this file you write this

    version: 2

    mkdocs:
        configuration: mkdocs.yml



