# Creating and Deploying an Atlas Cluster
1. Go to the Atlas [login page](https://account.mongodb.com/account/login) or [sign up page](https://account.mongodb.com/account/register).
2. Login if you already registered before, or Register of you don't have account on atlas.
3. On the top left part of the page: you can find orgnization dropdown field, to selec an orgnization or create one.\
![orgnizations position of atlas home page](./images/orgnizations-one-atlas-main-page.png)
  - Orgnizations used to orgnized your cloude projects clusters and teams, to determine authorizations for users.
  3.1 If you don't have an orgnization create one:\
  ![create new orgnization step 1](./images/create-new-orgnization-step-1.png)
  ![create new orgnization step 2](./images/create-new-orgnization-step-2.png)
  3.2 Add your orgnization name & select 'MongoDB Atlas' service: 
  ![create new orgnization step 3 (Adding name & select 'MongoDB Atlas' service)](./images/create-new-orgnization-step-3.png)
  ![create new orgnization step 4](./images/create-new-orgnization-step-4.png)
  ![create new orgnization step 5](./images/create-new-orgnization-step-5.png)
4. From orgnization dropdown field, you can shoose your new or old orgnization.\
![choose your orgnization](./images/choose-orgnization.png)
5. The orgnization projects table will apear, if you don't have any job the table will be empty.
  - One project is contain several clusters for the same project. Commonly one project used for one application. In the same Orgnization we may create several projects for the same app, one for development stage, another for testing stage and another one for production stage.
  5.1 Lets build new project by clicking on 'New Project' button:
  ![create new project by clicking on 'New Project' button](./images/create-new-project-step1.png)
  5.2 Name your project, and press 'Next' button:
  ![Name your project, and press 'Next' button](./images/create-new-project-step2.png)
  5.3 You will find your email set by default in the list of members who has access permission. So you can just Press 'Create Project' button:
  ![Ppress 'Create Project' button](./images/create-new-project-step3.png)
  5.4 Now your new project is created, and appear on projects drop down, like you see:
  ![project dropdown list](./images/projects-dropdown-list.png)
6. Press on you project that you want create your new cluster in.
  - The project can contain several clusters, and one cluster can contain several datasets (collections).
  ![Press 'Clusters' button from aside bar](./images/create-new-cluster-step1.png)
  ![Press 'Build a Cluster' button.](./images/create-new-cluster-step2.png)
  ![Press 'Go to Advanced Configuration' button.](./images/create-new-cluster-step3.png)
  ![Press 'Free' button.](./images/create-new-cluster-step4.png)
  6.1 Scroll down and press 'Cluster Details':
  ![Press 'Cluster Details' dropdown.](./images/create-new-cluster-step5.png)
  6.2 Naming your cluster, then press 'Create Cluster'
  ![Naming your cluster, then press 'Create Cluster'](./images/create-new-cluster-step6.png)
  6.3 Create a user for the Cluster, by: inserting your name -> inserting your password -> press 'Create User' button.
  ![Create a user for the Cluster](./images/create-new-cluster-step7.png)
  6.4 The cluster will set your IP Address automaticaly on IP Access List (you can modify it any time)
  6.5 Scroll down and press 'Finish and Close' button.
  ![press 'Finish and Close' button.](./images/create-new-cluster-step8.png)
7. Now you successfuly create your new cluster, and you now can see your clusters by click on 'Clusters' button on aside bar.
![click on 'Clusters' button on aside bar](./images/open-clusters-view.png)
![new cluster](./images/new-cluster.png)
8. You can create a sample of dataset (collections) on your new cluster by following these steps:
![press the 3 dots button](./images/three-dots.png)
![press 'Load Sample Dataset' button](./images/load-sample-dataset.png)
  8.1 Press select dropdown to choose the sample of dataset you want, on my case I will choole of them by click on chech box of *Select All* choice
  ![select dataset sample](./images/select-dataset-sample.png)
  8.1 Press on 'Load Sample Data' button, and wait for several minutes untile the data being ready.
  ![press load sample data button](./images/load-sample-data-button.png)
9. To browes the data on your cluster, go to your cluster and click on 'Browes Collections' button.
![Press 'Browes Collections' button.](./images/Browes-collection-button.png)
  9.1 Now you can discover your collections.
  ![collections list](./images/collections.png)
  9.2 Each collection contain documents. The single document is a one record on the collection.
  ![documents of a single collection](./images/documents.png)
