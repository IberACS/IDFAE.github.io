#### To create a new post :sunglasses:

- Create a .markdown file inside _posts folder.
- Name the file according to the standard jekyll format.
```
   2018-03-30-i-love-design.markdown
```
- Write the Front Matter and content in the file.
    ```
          ---
          layout: post | default | page
          title:  String Post Title
          date:   Time Stamp
          categories: String | Array of Strings Category / Categories
          ---
    ```

    ```
        ---
        layout: post
        title:  "The One with the Blackout"
        date:   2018-03-30 19:45:31 +0530
        categories: ["life", "friends"]
        ---
    ```  

####Create new pages, such a breeze! :smile:
- Create a .md file in the root directory.
- Name the file with the desired page link name.
```
   about.md
```
```
   design.md
```
- Write the Front Matter and content in the file.
```
          ---
          layout: page
          title: String Title of the webpage
          permalink: / String / Permalink for the webpage
          tagline: String Optional DevJournal Feature : Tagline for the page
          ---
```      
```
        ---
        layout: page
        title:  "Science"
        permalink:   /science/
        tagline : "Humanity is overrated."
        ---
```      
