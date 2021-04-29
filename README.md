# change_your_git_credentials

## Step 1

### For Apple

- Find your password confing on your Mac (for Apple) and remove them check this for an exemple remove them, you can clic
  [here](https://support.apple.com/fr-fr/guide/mac-help/mchlf375f392/mac) for see an exemple.

### For Window

- Find your credentials and remove them :

*in German, it is called: Anmeldeinformationsverwaltung  
*in French, it is called: Gestionnaire d'identification  
*in Polish, it is called: Menedżer poświadczeń  
*in Russian, it is called: Диспетчер учётных данных

- Then delete the entries under Generic Credentials.

## Step 2

- Open the terminal and tape `git config --global --edit`for see all your credentials like this:

<img width="570" alt="Screen" src="https://user-images.githubusercontent.com/61987773/116518259-50f79980-a8d0-11eb-87a5-f7e5a7255e32.png">

- Then tape `git config --global user.name "YOUR_USERNAME_ON_GITHUB"` for change your Name credentials.
- Then tape `git config --global user.email "YOUR_EMAIL_ON_GITHUB"` for change your Email credentials.

<img width="570" alt="Screen2" src="https://user-images.githubusercontent.com/61987773/116519032-47bafc80-a8d1-11eb-87f9-31dfea7af6be.png">

## Step 3

- Check with `git config --global --edit` if all is ok.

## Step 4

-In parent folder find the `.git`file and remove it

<img width="548" alt="screen3" src="https://user-images.githubusercontent.com/61987773/116523533-9fa83200-a8d6-11eb-9d5a-e0f53af0c524.png">

## Step 5

- Try to create a new repository on GitHub, if all is ok well done 👍, if not repeat the `Step 4 and then step 2`
