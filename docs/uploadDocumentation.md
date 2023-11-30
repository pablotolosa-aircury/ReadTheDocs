# Upload Documentation 

First of all you have to upload all your documentation to GitHub.
Once you have it done come [here](https://about.readthedocs.com/?ref=readthedocs.com) and create an account on ReadTheDocs page.

When you are signed up you have to click on "import a project" button from your dashboard

There we click on Connect to GitHub 

We log in on GitHub if necessary or just give ReadTheDocs permission to access our repositories (Note: The repository must be public if you want to use the free version of the tool). 

Then we select our repository and follow the instructions to deploy the Documentation page.

In the middle of the import, ReadTheDocs will ask us to add a .readthedocs.yaml file to your project.

 ReadTheDocs gives you an example showing which content your file must have. 
 
 You just have to create the file on your project folder and write this there (This is only valid if you are using mkdocs but if your using another software to make the documentation you may need to add more things that are on the example of readthedocs).

    version: 2

    build:
        os: ubuntu-22.04
        tools:
            python: "3.12"

    mkdocs:
    configuration: mkdocs.yml

Then we create a new commit and we upload it to the repository. Finally you click on Finish button.

 On the last step you just have to wait for the compilation and you will have your documentation done and deployed.






