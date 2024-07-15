# Odoo-Apps-Publish
Odoo Application publishing Script


1. Log in to odoo apps
username:      password:

2. Create a folder and open cmd here

3. Clone github 
go to cmd and write command: 

git clone (link) --branch 14.0

4. After getting the folder go to selected app:
Open the selected module in a editor (VS code or Pycharm)

5. Go to manifest file and put here author name, company  name, price, version name etc

6. Do the selected tasks:

Go to Static > description and edit icons
Go to images edit screenshots
Go to index.html for edit the image link and captions

7. For banner, edit banner image to an editor and put it in description

8. Push repo to github:
go to cmd and give commands,

git add -A
git commit -m "update module"
git push

9. Scan apps:
Go to odoo apps then Dashboard > Scan 

10. See the app in New apps

