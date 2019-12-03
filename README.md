# resume-portfolio-angular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli), for Portfolio and showcase.
This is specially for Developers who can showcase their portfolio online.

# Demo
You can check demo on https://sumedha-prithyani.github.io/resume-portfolio-angular/

# Make your own portfolio with this

You can make your own same portfolio with this template. Follow given steps -
1. Fork the repo - resume-portfolio-angular
2. Host the forked project on your domain or using git pages like I did. For git pages you can follow (https://alligator.io/angular/deploying-angular-app-github-pages/).
3. Once you are done with hosting these files you can see your site with Profile info, experience, showcase, education, skills section with dummy data as "lorem ipsum..".
4. Just go to files inside assets folder and update json file, replace lorem ipsum with your information. There are 6 json files each for data showing on site for Profile info, experience, showcase, education, skills section.
5. If you wish to hide any section go to assets/information.json file and disable the section by setting it false.

# Update images for showcase on Portfolio section
Go to assets/img/images folder and upload screenshots/picture/images of your work.
Remember to add those uploaded image's name in key "src" in your portfoliolist.json file as well.

You can check assets/portfoliolist.json "sublist" is mandatory while "subimg" is optional, if you are putting data in "subimg" make sure to set "more" key as true in it's "sublist".
