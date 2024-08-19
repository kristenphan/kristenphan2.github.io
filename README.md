# Subdomain takeover example
Template repo for taking over domain https://kristen.ddns.net/

## How-to
### Step 0: Confirm that the domain is available for takeover
- If https://kristen.ddns.net/ shows error "404 - There isn't a GitHub Pages site here.", it means the domain is pointing to a non-existing GitHub Page and can be taken over.

![Alt text](/resources/step0.png)

### Step 1: Fork this repo into your GitHub account
- Repository name: You can name the repo however you like

![Alt text](/resources/step1a.png)

![Alt text](/resources/step1-2.png)

### Step 2: Create a GitHub Page for the forked repo
- Go to Settings > Pages
- Configure the GitHub Page:
  - Source: deploy from a branch
  - Branch: main
  - Custom domain: kristen.ddns.net > Click "Save"
  - Enforce HTTPS: checked
- Go to https://kristen.ddns.net/ to check if you have successfully taken over Kristen's domain. 

![Alt text](/resources/step2a.png)

![Alt text](/resources/step2-2.png)

This is what Kristen's domain should show after you've taken it over. 
![Alt text](/resources/step2c.png)

### Step 3: Remove your GitHub Page's custom domain
- Go to Settings > Pages
- Remove the custom domain of your GitHub Page so that someone else can attempt to take over Kristen's domain.

![Alt text](/resources/step3a.png)

  
