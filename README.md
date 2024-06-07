# 💻 Umbraco Repo Template 
This is a GitHub Template repo - that when new repos are created from this template will trigger a GitHub Actions build and scaffold the necessary files to have a project ready to work with for Umbraco v14+ package development

## How do I use this ?
* Click the Use this Template button from the GitHub repo page here and select Create a new repository.
* Alternatively [follow this link and give your new repoistory a name](https://github.com/new?template_name=Umbraco-Repo-Template&template_owner=warrenbuckley)

## What happens when I use this repository template
* GitHub Actions immedaitely run and peform steps to setup an Umbraco project ready for package development
* You can see each indvidual step to follow along to see what it is doing on your behalf
* Commits the changes to the main branch
* Disables the GitHub Action so it never runs again

## What does it create for me ? 
| Project | Notes |
|--------|--------|
| REPO.Website | This project is an sample Umbraco site that allows you to easily test the site |
| REPO.Now | This is an RCL that the client project will copy files into wwwroot. This projects can be used to write any C# code such as APIControllers |
| REPO.Client | Open this folder with VSCode editor and start working with the TypeScript files to extend Umbraco backoffice |

## Its finished, now what?
- [ ] Clone the repository down to your local machine
- [ ] Open the Solution file with Visual Studio or Jetbrains Rider
- [ ] Build the Solution
- [ ] Run the Website project
- [ ] Install Umbraco with a user and preferred database type
- [ ] Once logged into the backoffice, open your browser dev tools and notice the hello world message in the console
- [ ] Ensure NodeJS is installed - recommend using 20.x LTS version
- [ ] Navigate to the `Client` folder
- [ ] Run `npm install`
- [ ] Run `npm run watch` Vite is now watching the TypeScript files
- [ ] Ammend the index.ts file and update the comment of the console.log
- [ ] Watch as the page will reload and your new message appears in the console
- [ ] Go forth and happy hacking

## Other resources
* [Umbraco Docs](https://docs.umbraco.com/umbraco-cms/tutorials/creating-a-custom-dashboard)
* [UUI Library](https://uui.umbraco.com/?path=/docs/uui-action-bar--docs)
* [V14 Storybook Docs](https://apidocs.umbraco.com/v14/ui)

---

_Lovingly crafted for you by [Warren Buckley](https://github.com/sponsors/warrenbuckley)❤️_<br/>
_[Available for hire](https://hackmakedo.com/)_
