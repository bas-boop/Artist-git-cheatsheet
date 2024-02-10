# Artist git cheatsheet
This is little document to help artist use some git stuff. Mostly about pull requests.

- [Pull request](#pull-request)
  - Where to make?
    - [Browser](#browser)
    - [Github desktop](#github-desktop)
  - [Making a pull request](#making-a-pull-request)
  - [Apply feedback](#apply-feedback)
- [Rename file](#rename-file)
- [Wrong folder](#wrong-folder)
- [Prefab](#prefab)
- [Meta files](#meta-files)

# Pull request

When you have commit on your branch, you need to make a pull request. This is done so others can check your work and intregrate it into the project.

There are 2 ways to make a pull request:
- [browser](#browser)
- [github desktop (or other version control application)](#github-desktop)

## Browser
After commiting your branch and going to the project repo, you will see the following:
<details>
  <summary>Open a pull request suggestion</summary>
  
  ![image](https://github.com/bas-boop/Example/assets/70578065/76e6150b-32bf-46cd-9fa0-6d1b02cc932a)
</details>
Click on this green button. You can now go so the next step.

[next step](#making-a-pull-request)

## Github desktop
After commiting your branch you will see this blue button, click on it.
<details>
  <summary>Make pull request button</summary>
  
  ![image](https://github.com/bas-boop/Example/assets/70578065/21f15059-7ef0-409f-a962-9ab999df2507)
</details>
You can now go so the next step.

[next step](#making-a-pull-request)

## Making a pull request

<details>
  <summary>Making a new pull request</summary>
  
  ![image](https://github.com/bas-boop/Example/assets/70578065/b3ac60d7-60bb-4fbe-b832-920d69f5d19e)
</details>

When making a pull request you see something like this image above. You can do the following steps.

- Assigin yourself (this will make easy to see whos pull request it is)
- Add labels (like a `art` or `ready for review` label)
- If having only 1 commit, you can rename the pull request to the branch name. (In this case `art/poster-model`)
- Add a reviewer, a lead artist or git master.
- If needed, added a description. (List of assets added. Or tell the changes made to an existing asset.)

<details>
  <summary>Finnished pull request</summary>
  
  ![image](https://github.com/bas-boop/Example/assets/70578065/464ae66d-df97-4565-9fc6-4e3dcc834a1b)
</details>

Now create the pull request and wait for someones review or approval.

## Apply feedback

After getting some feedback and applying it, you can resolve the comments. This makes sure that you and others know what feedback you have applied.
<details>
  <summary>Old feedback</summary>
  
  ![image](https://github.com/bas-boop/Example/assets/70578065/97ae8e57-7115-46d8-95d6-9066cdefb9d3)
</details>

# Rename file
<details>
  <summary>Renaming feedback</summary>
  The red line are the folders of the asset.<br>
  The green line is the model.<br>
  
  ![image](https://github.com/bas-boop/Example/assets/70578065/2be40652-0e01-4fcb-895a-b1251534537a)
  Now you can rename the asset and commit again or apply more feedback.
</details>

# Wrong folder

<details>
  <summary>Wrong folder feedback</summary>
  The red line are the folders of the asset.<br>
  The green line is the model.<br>
  
  ![image](https://github.com/bas-boop/Example/assets/70578065/46bfa835-e432-4880-bdbb-4d763c186d6d)
</details>

To fix this simply move the textures into the right folder.
> If there are many textures that are similar, you should make a subfolder. In this case `textures/posters` .

# Prefab
Make art into prefab so it can be used. To do so, follow the steps:
1. Have a Unity scene open.
2. Drag your assets with all settings or textures ect ready.
3. Drag your assest form the `hierarchy` window into the `project` window, this should be done with the correct folder open. (Prefab)
4. Test your prefab, if nothing wrong, make a commit.

# Meta files
A meta file is an Unity auto generated file that will be made when adding any file into the project. If they are missing there will be problems.

<details>
  <summary>Missing meta file</summary>
  
  ![image](https://github.com/bas-boop/Example/assets/70578065/87bfdf17-f4e7-446e-98f2-a563cf89751b)
</details>

To fix this, simpley open Unity and commit the generated meta file.
> This should not be a problem, because you need to test your art inside Unity before commiting.
