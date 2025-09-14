What triggers this workflow to run? (Look at the on: section)
    In basic words, any change that will go into the main branch will make this run.This workflow will work automatically when you make or update pull requests that will merge into main or you push changes to the main brach. 
What are the four main steps this workflow performs? (List each step name)
    The four main steps that this workflow performs are firstly ,getting the repository code, which means to get all the previous code. Then it validates the HTML looking for any coding mistake and later it will check it there is any broken link inside the files. Finally, it will get ready the site for its deployment in GitHub, checking if any permissions are needed or any other conditions.
What does the "Checkout code" step do and why is it necessary?
    It is necessary because it copies your project files to the workflow runner, and without this, the workflow can not check or deploy the code.
What is the purpose of the environment configuration?
    The purpose is tell GitHub how and where it has to deploy the project. It helps with some security tasks, as tracking the live site URL, its deployment statutes, and managing permissions for a safely deployment.
How does this automated deployment improve reliability compared to manual deployment?
    This automated deployment will make sure that all the deployments make will foloow the same process. It checks for erros and prevents humans mistakes. After that, GitHub will show you a status report where you can know if it worked or not.
What would happen if you pushed code to a different branch (not main)?
    This means that the workflow will not deploy your website, so basically, the website will not update. The deployment only happens if you push the changes into main.