# How to Write README.md file using Typora .

### 1. Install Typora 

#### 1.1. On Linux OS:

- open the terminal by **CTRL+ALT+T** and write this command:

```
# First add Typora's external repository to your system's list of package sources.

sudo add-apt-repository 'deb https://typora.io/linux ./'
sudo apt-get update

# Then install typora
sudo apt-get install typora
```

> Hint: This command will ask you for your user password.

But you **may** face this error:

![Screenshot from 2023-12-24 14-54-27](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/faae6384-5f8c-402a-9892-00401273fe22)


- Solve this issue by use ***snap*** package manager instead of ***apt***  [SOLVED] 

```
sudo snap install typora
```

then the **snap** will download **typora** and install it.

![Screenshot from 2023-12-24 14-56-53-1703444980032-8](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/d6d4c16d-53b1-4e20-9e12-24b98d6530d1)


#### 1.2. On Windows OS:

- Go to the typora Website [clickHere](https://typora.io/) , download your suitable version (Win 64bit or 32bit) and install it.

  ![Screenshot from 2023-12-24 21-06-24](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/59ae9e3b-b9d2-4199-ad35-168289d06741)


### 2. Open typora 

- write ***typora*** on the terminal to open the application in case of Linux OS.

```
typora
```
![Screenshot from 2023-12-24 14-58-06](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/9e96b168-ea15-44ff-b904-c940840dc410)

![Screenshot from 2023-12-24 16-05-42](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/da00ad44-2f7d-43cb-8c5d-8c0c301816ef)


> From Here In case of Linux or Windows OS.

#### 2.1. Heading 

- You can select the font heading from **paragraph** in the tool-par as follow :

![image-20231224155834157](README.assets/image-20231224155834157.png)

Or use a number of (# )signs before of a word or phrase. Take care about the space after # sign. 

[# anyWord : Heading 1]

[## anyWord : Heading 2], and so on...etc.

- # Heading 1 (# )

- ## Heading 2       (## )

- ### Heading 3           (### )

- #### Heading 4                 (#### )

- ##### Heading 5                          (##### )

- ###### Heading 6                          (###### )

#### 2.2. Tables 

- You can select **Table** from **paragraph** in the tool-par as follow

![Screenshot from 2023-12-24 16-13-29](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/8e3bb8c1-6a09-488d-877a-6d6067633065)

- Then select **Insert Table** and determine the number of columns and rows as you want.
![Screenshot from 2023-12-24 16-15-43](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/657d9336-d387-4525-9a50-c33844f39902)


| **Column 1 , Row 1** | **Column 2 , Row 1** | **Column 3 , Row 1** |
| :------------------: | :------------------: | :------------------: |
| **Column 1 , Row 2** | **Column 2 , Row 2** | **Column 3 , Row 2** |
| **Column 1 , Row 3** | **Column 2 , Row 3** | **Column 3, Row 3**  |
| **Column 1 , Row 4** | **Column 2 , Row 4** | **Column 3 , Row 4** |

#### 2.3. Code Fences

```
# The area which you can write a certain command or code,as the example below
```

```
sudo apt install python3-pip
```

- Another example:

```c
#include <stdio.h>
int main(void)
{
    printf("This is an example of Code Fences ! \n");
}
```
- You can select the Programming Language as you like 
![Screenshot from 2023-12-24 20-09-45](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/b6c0e4ea-d4df-47ac-96cf-f34218ae3b03)
- you can select **Code Fences** from **paragraph** in the tool-par as follow: ![Screenshot from 2023-12-24 16-35-02](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/3aba3591-19fb-45c1-9d28-5b840cd403e0)


#### 2.4.  List

##### 2.4.1. Ordered List 

Arrange some of points by order like that:

1. First Point.
2. Second Point.
3. Third Point.     

##### 2.4.2. Unordered List

- First Point.
- Second Point.
- Third Point. 

##### 2.4.3. Task List

- [x] Task 1 Done.
- [x] Task 2 Done.
- [ ] Task 3 Done.

##### 2.4.4. List Indentation

- First Point.

  - First Part of First Point.
  - Second Part of First Point.
  - Third Part of First Point.

  You can Select those options from **paragraph** in the tool-par as follow:![Screenshot from 2023-12-24 18-06-47](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/cd733c11-784f-406f-ac41-47c8a26a5e25)


#### 2.5. Quote

> This is a form of Quote, you can write anything here to notify the reader for anything you want.
>
> Note that, In my opinion there is not only specific way to make a professional README.md file, But definitely the the most mistake is not include your README.md file with your project.

You can Select Quote option from **paragraph** in the tool-par as follow:
![Screenshot from 2023-12-24 19-21-44](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/c0e0f108-326d-468c-a965-374288628d0c)


OR You can use right arrow sign (>) before the sentences.

#### 2.6. Hyper Links

- The syntax of create hyper-link as follow:
![Screenshot from 2023-12-24 18-17-01](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/b9e401c7-e027-45a7-93af-960cd6f3fb60)
  
- Example:  [MyLinkedInAccount](https://www.linkedin.com/in/anas-khamees12/)  
  ![Screenshot from 2023-12-24 21-24-28](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/7c8cab03-f561-49bd-a1da-813949495bf1)
  
- Or you can Select Hyper Link option from **Format** in the tool-par as follow:
![Screenshot from 2023-12-24 18-24-24](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/bfaacc9e-6bfe-46c5-b0e0-4f8c7a45ee8b)


#### 2.7. Insert Images

> There are many methods to insert images to README.md file, also you can drag the images and drop them on the Github server directly by Select **Edit file** and drop the image in any position in the file.
> **This is the easiest way**
> ![Screenshot from 2023-12-24 21-38-00](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/7e4348c1-c79c-4200-8d05-355aa86e9728)


- #### Insert the images using Typora

  - Select **File** from the tool-bars then select **Preferences** 
![Screenshot from 2023-12-24 20-14-38](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/9131f1a7-827b-402f-8e6b-9f868e4400f1)

  - Select **Image**, then change the ***When Insert Images*** option to: **Copy image to ./${filename}.assets**
![2023-12-24 at 22 04 28](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/ca308272-7b3c-4103-8121-dd1fd57f1397)

    > **Copy image to ./${filename}.assets** option creates folder automatically called ***README.assets***    to save the all images used in README.md file, this assets folder is uploaded with the Repo to provide Github server with images source.

    ![22 41 47(1)](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/30f9e275-afa6-4495-b3a7-9a805ed8ad78)


  - If you forget to select **Copy image to ./${filename}.assets**  option and added the images already, Don't worry :

    > Select the image and Right Click on it, then select this option: **Copy to README.assets**.
    >
    > This Option copies The images to **README.assets** folder automatically.
    ![22 25 46](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/fea0efc9-3a27-4ff3-bb17-4f785fdef643)


  - Finally  Select **Image** then **Insert Image** option from **Format** in the tool-par as follow:
  ![image-20231224225908734](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/4a53c41c-d4ff-4972-a5ad-410d98a35c21)


  - Click on the URL icon to select your Image as follow: 

  ![image-20231224230515787](https://github.com/anaskhamees/Creat_README.md_Typora/assets/52020047/dc1a4856-d556-4940-a12d-3dd0828bcb0f)






TO BE CONTINUED   . . . . . . . . . . .
