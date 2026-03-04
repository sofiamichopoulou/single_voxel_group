# Single Voxel Group Website

## Purpose and scope

 This is the GitHub repository for the Single Voxel Group website (<https://sotnir.github.io/svg>). The website serves as a central hub supporting information sharing, event announcements, and access to shared resources.

 The website is maintained by volunteers and is intended as a neutral platform. It does not set academic direction, research priorities, group strategy, or leadership decisions, and functions solely as a support and communication resource for the community.

 ## Roles and responsibilities

 - Website maintenance is carried out by the web working group, which is open to all members of the Single Voxel Group.
 - The working group is volunteer-based, with responsibilities shared and distributed to avoid reliance on any single individual.
 - The web working group is responsible for:
   - Publishing workshop-related content
   - Technical maintenance and updates
   - Improving website usability, accessibility, discoverability, and integration with other relevant platforms.

## Content review frequency

- Website content is reviewed and updated on a *quarterly* basis (every three months) or aligned with workshop schedules.

## Maintaining this website

### How to run the website locally for development

#### Visual Studio Code (GUI)

1. Visit https://code.visualstudio.com/, and download the version appropriate to your operating system.
2. Install [Live Server Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in Visual Studio Code after it has been installed successfully. To do so, go to the Extension tab on the left navigation bar. Search “Live Server”, and the extension should show up on the list. Click on install.
3. After the extension has been installed, click the "Go Live" button appeared at the bottom right corner. This button should appear every time you open the files folder that contains the website.
4. A web browser should be launched, and now you should be able to preview the website within the local live server environment.

#### Python (CLI)

**Note**: You'll need to first install [Python 3](https://www.python.org/downloads/). 

Alternatively, you can launch a local HTTP server via the command line.

1. Open a terminal or command prompt and navigate to the website directory:

```
cd /path/to/website/folder
```

2. Run the following command:

```
$ python3 -m http.server
```

You should see output similar to:

```
Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ...
```

3. Visit the address shown above to view the website locally.