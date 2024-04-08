<h1 align="center"> static.deriv.com </h1>

A repository for digital marketing codes, email templates, images, company PDFs...

## In this document:
- [Quick start](#quick-start)
- [How to contribute](#how-to-contribute)
- [Manage releases](#manage-releases)
- [Test link deployment](#test-link-deployment)
- [Other documents](#other-docs)

## Quick start
1. **Fork the project**

    In order to work on your own version of the Deriv application, please fork the project to your own repo.

2. **Clone using SSH**

    ```sh
    git clone git@github.com:your-github-username/deriv-static-content.git
    ```

3. **Enter project directory**

    ```sh
    cd deriv-static-content
    ```

4. **Install your dependencies: not necessary, just to test and debugging purpuse**

    ```sh
    npm install nodemailer
    ```

## How to contribute
We contribute by PR (Pull Request):

1. Create branch from the latest `master` branch
```sh
git checkout master
git pull origin master
git checkout -b [_your_branch_name]
```

2. Make your changes

3. Make pull request

- Push your changes to *your* origin (your fork), add `-u` flag for the first time push

```sh
git add . 
git commit -m "short description"  
git push -u origin [_your_branch_name]
```

- Click on the autogenerated link from the terminal to open the PR

## Test link Preview
By Vercel CLI can have a preview then add to cards to check by Requesters, stakeholders or PMs.

## Other documents:
- [File paths for images, pdf, email templates,...](https://github.com/deriv-com/deriv-static-content/blob/master/doc/file-structure.md)
