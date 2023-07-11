https://medium.com/design-with-figma/the-ultimate-guide-to-designing-data-tables-7db29713a85a

https://www.mobilespoon.net/2019/11/design-ui-tables-20-rules-guide.html

--- 

### How to design data tables that don't suck - the 20 rules guide

- [November 18, 2019](https://www.mobilespoon.net/2019/11/design-ui-tables-20-rules-guide.html "permanent link")

  

  

  

[![How to design data tables that don't suck - the 20 rules guide by the mobile spoon](https://1.bp.blogspot.com/-QaV-ux_CSBY/XdTjUPBkfRI/AAAAAAAAQFI/iyy_ctwAeocMygGZPcLN3nPboFIMHAlJQCLcBGAsYHQ/s16000/designing%2Btables%2B-%2Bthe%2Bmobile%2Bspoon.png "How to design data tables that don't suck - the 20 rules guide by the mobile spoon")](https://1.bp.blogspot.com/-QaV-ux_CSBY/XdTjUPBkfRI/AAAAAAAAQFI/iyy_ctwAeocMygGZPcLN3nPboFIMHAlJQCLcBGAsYHQ/s1600/designing%2Btables%2B-%2Bthe%2Bmobile%2Bspoon.png)

  

  

**20 rules for designing and developing great data tables.**   
  
Tables and grids have always been an important UI component for products and dashboards.  
And yet, even today, it’s easy to find data tables that are badly designed or deliver an inadequate user experience.  
  
I came up with the idea to write this **UI guide** (which was written a thousand times before, but not as brilliantly as I'm going to write it...) while doing some maintenance work for our [product](https://www.mobilespoon.net/2018/10/missbeez-hottest-startup-in-tel-aviv.html "Missbeez - hottest startup in Tel Aviv") (yeah, in our startup, the most senior person does the cleaning...).  
  
Anyway...  
  
I went through over **30 different SeaS tools and SDKs that we're using** and played with their dashboards to review some numbers, collect some insights, and make minor modifications. I couldn’t help but notice how bad those tables were implemented, in terms of UI design and basic functionality (and those are good Saas products I'm talking about).  
  
Given that I’ve been developing (and using) tables for 20 years (yes, I know I'm old, one day you'll get old too...) - I decided it’s time to summarize the most basic UI/UX rules that are simply a must-have for every product that deals with tables and grids.  
  
And since I'm celebrating 20 years in software - I figured 20 rules would be sufficient...  
  
This guide will focus on generic **functionality**, overall **design**, and **aesthetics**.  
  
Let’s dive in:  
  

## **Functionality:** 

  

### **1. Start with Sort and Filters:** 

Yes, I know sort and filters are annoying, I hate them too, but that’s why they need to come first (unless, of course, you plan on having a fancy table with less than 10 records or something like that...).  
  

[![Start with sort and filters](https://1.bp.blogspot.com/-CeURlT65xzo/X4jMtpn2UAI/AAAAAAAARDg/p0GbX8xBAQoM2kC9UTRQ4lYRhFmofCsDgCLcBGAsYHQ/w640-h296/sort%2Band%2Bfilters.png "Start with sort and filters")](https://1.bp.blogspot.com/-CeURlT65xzo/X4jMtpn2UAI/AAAAAAAARDg/p0GbX8xBAQoM2kC9UTRQ4lYRhFmofCsDgCLcBGAsYHQ/s1600/sort%2Band%2Bfilters.png)

If you can't sort and filter, you can't find anything  

  

  

Sort and filters go beyond usability or ease of use - they are **key functionality for digesting the data**: understanding trends, comparing records, and finding specific values. You can't do those things without sort capabilities and filters.

  
If adding column-based filters (based on the meta-data such as dates, booleans, strings, etc.) is too costly, start with something more basic such as a modern search box (that filters in the matching rows) or a few hardcoded filters based on common use-cases.

  

  
Hey, have you heard about [the host syndrome](https://www.mobilespoon.net/2022/01/the-host-syndrome.html)? If not make sure to check it out [here](https://www.mobilespoon.net/2022/01/the-host-syndrome.html). 

  

### 2. Make sure your columns are resizable

This one comes down to viewing pieces of information without having to drill down into each record (which makes the experience horrible!).  
  
No matter how large are your column widths - there are always going to be cases where the users will need to expand them further so make sure your table columns are not fixed because that’s just being weird.

  

[![Make sure your columns are resizable](https://1.bp.blogspot.com/-EgKiWojO-iQ/X4jM_nUZ24I/AAAAAAAARDo/SsTQMnOINl8V8jaHTu2e2bcP-pPPdtKpwCLcBGAsYHQ/w640-h298/columns%2Bresizable.png "Make sure your columns are resizable")](https://1.bp.blogspot.com/-EgKiWojO-iQ/X4jM_nUZ24I/AAAAAAAARDo/SsTQMnOINl8V8jaHTu2e2bcP-pPPdtKpwCLcBGAsYHQ/s1600/columns%2Bresizable.png)

If you can't resize, you can't read  

  

  

### **3. Allow columns reorder** 

For large tables, one size **doesn’t** fit all.

  

[![Allow column reorder](https://1.bp.blogspot.com/-zyIaL88RpFc/X4jNoyaCjUI/AAAAAAAARD0/GOQ7oGscL3wini-rML9HT7DiZNFyN-knwCLcBGAsYHQ/w640-h296/columns%2Breorder.png "Allow column reorder")](https://1.bp.blogspot.com/-zyIaL88RpFc/X4jNoyaCjUI/AAAAAAAARD0/GOQ7oGscL3wini-rML9HT7DiZNFyN-knwCLcBGAsYHQ/s1600/columns%2Breorder.png)

Different users need different column order

  

With column reordering, users are able to configure the table to fit their specific needs. This relatively small feature can reduce clutter and save some back-and-forth scrolling.

  
Here, again, the name of the game is digesting a large amount of information. Reordering columns allows users to focus on certain areas and digest smaller portions of the information.  

  

  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjvnQJGIKH-4dAzw1z546DzlRwv2uhBb8vGCw1lpaYhsqSVYrYtv9hiPiCn9UZBuAxWrXnBmk-1BQ8UqiZwfhkmnhrecGoFtiyfhb9vvn1FyELDQd6ErLUvY7MpAfkUh4uy8SIYx-w3rzLWqZzfme6yuxIYq1ylTJY-QVXRFznmQlAZI6B2pVgauy6l/s320/Quant%20with%20Watch.png)](https://apps.apple.com/us/app/quant-your-fitness-dashboard/id1406705309)

Check out [Quant](https://apps.apple.com/us/app/quant-your-fitness-dashboard/id1406705309) - a [fitness dashboard for Apple Watch](https://apps.apple.com/us/app/quant-your-fitness-dashboard/id1406705309)

  

### **4. Inline editing**

There are many UI solutions for editing table cells: inline boxes (bad when dealing with endless rows), popups (annoying), expandable sections (meh), and others.  
  
I don’t think there’s one best practice for this pattern as it depends on the functionality, the data types, and the use cases, but one of my favorite alternatives (especially as a user) is having a side view (quick view) that pops in from the side once an item is selected.

  

[![Allow inline editing - designing data tables](https://1.bp.blogspot.com/-MtvpRt1LEUc/X4jOB1289BI/AAAAAAAARD8/tXsfM5HZkTQ3cGATDG81yB6KgC2jDj0zACLcBGAsYHQ/w640-h292/inline%2Bediting.png "Allow inline editing - designing data tables")](https://1.bp.blogspot.com/-MtvpRt1LEUc/X4jOB1289BI/AAAAAAAARD8/tXsfM5HZkTQ3cGATDG81yB6KgC2jDj0zACLcBGAsYHQ/s1600/inline%2Bediting.png)

  

  

What I like the most about this option is that it maintains the context (unlike popups), easy to use (forms are easy), and works well even for a large number of fields is presented in a vertical scroll view.  

  

  

Check this all-in-one video guide: 

  

  

## **Design**

  

### **5. Design for small screens**

Sure, it’s more convenient to design and develop when connected to gigantic displays, but think about the users with laptops or iPads - what did they do wrong!?  
  
Endless scrolling (horizontally and vertically), shrunk columns, hidden texts, those can all ruin the experience and annoy your users, so make sure to check your design on small screens and definitely try to use it for a while with real data (rather than the usual “aaa” and “bbb”).  
  
If it’s really bad - you may need to get creative with those usability problems, so you better know them in advance.  
  
  

### **6. Anchor some identifiers with fixed headers and “frozen” columns**

So going back to my point about the screen size - your table needs to remain friendly when presenting a large amount of data on any screen.  
  
To skim through the data, users will need to scroll a lot (vertically and horizontally), which means they’ll need some **anchors** to find their way around:  

-   Column headers must be **fixed** when scrolling down (basic, I know, but just in case)
-   The first column(s) should be **locked** (“frozen” as MS Excel and Google Sheets call it) so when you scroll horizontally you still have the context of the row. 
-   Include a **full-row selection** option to mark the important rows while scrolling horizontally. This one might become a bit tricky if clicking the row does something else like expanding it or drilling down. Nevertheless, if your table is horizontally long, the users will want to highlight a row and start scrolling while it’s highlighted. Excel and Sheets do it by adding a special selection area on the left, but web-based tables not always have that option so you may consider an alternative such as having a check-box in each row for selecting items and highlighting them. 

  

[![Think about laptops in your designs - use frozen columns](https://1.bp.blogspot.com/-z9qg6AjPYAg/X4jO5widKwI/AAAAAAAAREM/g5v_qsEqnlYktqLnMevAnSoUt5Z7GChgQCLcBGAsYHQ/w640-h292/frozen%2Bcolumns.png "Think about laptops in your designs - use frozen columns")](https://1.bp.blogspot.com/-z9qg6AjPYAg/X4jO5widKwI/AAAAAAAAREM/g5v_qsEqnlYktqLnMevAnSoUt5Z7GChgQCLcBGAsYHQ/s1600/frozen%2Bcolumns.png)

You use large screens, but your users might use laptops and tablets  

  

  

### **7. Color alternating rows** 

When using large data tables it’s easy to get lost.  
Zebra striping can help the users keep their place, but the colored rows must be very light, otherwise, they will cause clutter and might look like selected rows.

  

[![Color alternating rows - table design guide](https://1.bp.blogspot.com/-orZPYoIeG_0/X4jOW6A9hHI/AAAAAAAAREE/G0GkM-uDvec1FlKLFkQCs1gPdJ_H9x3kgCLcBGAsYHQ/w640-h296/color%2Balternating%2B.png "Color alternating rows - table design guide")](https://1.bp.blogspot.com/-orZPYoIeG_0/X4jOW6A9hHI/AAAAAAAAREE/G0GkM-uDvec1FlKLFkQCs1gPdJ_H9x3kgCLcBGAsYHQ/s1600/color%2Balternating%2B.png)

  

Use a very lite color, avoid using black lines and dark borders, and instead set everything to light gray.

  

  
[read: [40 UI/UX rules for designing and writing text in products](https://www.mobilespoon.net/2018/11/ux-writing-comprehensive-guide-for.html)]

  

###   

### **8. Set a fixed row height**

Tables and grids are about **structured information**, but when a table has too many column widths and different row heights - things become **messy** and the information feels **less structured**.  
  
While I believe the resizable columns are a must - having resizable rows is a different story: it adds another dimension and might confuse the users more than it's helpful.  
  
So for the sake of overall usability and aesthetics, I believe all the rows should have the exact same height, regardless of the content.

  

[![Fixed rows are better for skimming and reading](https://1.bp.blogspot.com/-N0LQnHMbglo/X4jPqvC1m5I/AAAAAAAAREU/9-2BCE9va4Mr-4hmW7qdQd3LFF_uLtzQwCLcBGAsYHQ/w640-h298/fixed%2Brow%2Bheight.png "Fixed rows are better for skimming and reading")](https://1.bp.blogspot.com/-N0LQnHMbglo/X4jPqvC1m5I/AAAAAAAAREU/9-2BCE9va4Mr-4hmW7qdQd3LFF_uLtzQwCLcBGAsYHQ/s1600/fixed%2Brow%2Bheight.png)

Fixed rows make it easier to scan and review large tables  

  

  
To better support multiline text chunks consider the following:  

1.  Replace new lines with space and turn the whole text into one line (that can be viewed by resizing the column width).
2.  Turn the row height (of all the rows) to 2 lines instead of 1 (which will only solve some scenarios).
3.  Use tooltips (no, forget that. Tooltips are lame).
4.  Consider an option to expand/collapse a row by clicking it (which might be a needed functionality anyway).
5.  Consider an option to show the details of the selected row using a floating side view as mentioned in rule number 4.

  
  

## **Aesthetics** 

Aesthetic design leads to better usability.  
Here are a few ways to get rid of the clutter and improve content readability through simple UI design modifications:  
  

### **9. Increase cell padding** 

Whitespaces again. Yes, again.  
Tables loaded with information are exactly where your users will want to see some more whitespaces even if it costs them some extra scrolling.

  

[![Increase your cell padding - the table design guide](https://1.bp.blogspot.com/-wncXxKrYJTQ/X4jQGpKCK3I/AAAAAAAAREg/HMiNgJP516kVJlnBZba1-reUXyKiYsaGgCLcBGAsYHQ/w640-h296/cell%2Bpadding.png "Increase your cell padding - the table design guide")](https://1.bp.blogspot.com/-wncXxKrYJTQ/X4jQGpKCK3I/AAAAAAAAREg/HMiNgJP516kVJlnBZba1-reUXyKiYsaGgCLcBGAsYHQ/s1600/cell%2Bpadding.png)

  

  

[Read: [84 cognitive biases that will help you design better-converting products](https://www.mobilespoon.net/2019/04/collection-cognitive-biases-how-to-use.html?showComment=1572509751128#c8154181890336078095)]  
  
  

### **10. Get rid of unnecessary borders**

Once the data is well structured and the whitespaces are in-place - it’s time to get rid of those redundant borders or at least make them super thin and with light colors

  

[![Borders add to the overall clutter - get rid of them](https://1.bp.blogspot.com/-Y1dKJYV9c6s/X4jQTMNwrFI/AAAAAAAAREk/o7d0s9Cqm6gHH4PBkeZpNRLM9x25J42iwCLcBGAsYHQ/w640-h296/get%2Brid%2Bof%2Bborders.png "Borders add to the overall clutter - get rid of them")](https://1.bp.blogspot.com/-Y1dKJYV9c6s/X4jQTMNwrFI/AAAAAAAAREk/o7d0s9Cqm6gHH4PBkeZpNRLM9x25J42iwCLcBGAsYHQ/s1600/get%2Brid%2Bof%2Bborders.png)

Borders increase clutter - get rid of them  

  

  

### **11. Turn black into dark gray**

Black color increases eye strain, and if it comes together with borders and frames - it’s a UI disaster.  
Make everything fine and gentle so the table feels less noisy and helps users focus on the content.  
  

[![Turn black into dark gray - the table design guide](https://1.bp.blogspot.com/-RwUCgcDP974/X4jQxVOlTDI/AAAAAAAAREw/lNOaQf89Xg4QkVkS9oz4J9iJ_rw8QVkZgCLcBGAsYHQ/w640-h296/remove%2Bblack.png "Turn black into dark gray - the table design guide")](https://1.bp.blogspot.com/-RwUCgcDP974/X4jQxVOlTDI/AAAAAAAAREw/lNOaQf89Xg4QkVkS9oz4J9iJ_rw8QVkZgCLcBGAsYHQ/s1600/remove%2Bblack.png)

Replace black with dark gray

  

  

This tip is also relevant for dark modes where dark gray backgrounds are often easier on the eyes than full black.  
  
More about that in this beauty: [visually distorted - when symmetrical UI looks all wrong](https://www.mobilespoon.net/2019/08/visually-distorted-when-ui-looks-all.html).  
  
  

### **12. Text should be vertically aligned to the top**

In case you plan on having 2-3 lines per cell, make sure they are all aligned to the top, otherwise, you’ll end up having cells where the text starts from the middle line, next to cells where the text starts from the first line, creating an inconsistent experience.

  

[![Align text to top of cell](https://1.bp.blogspot.com/-pc55xSq26yw/X4jRUbETBoI/AAAAAAAARE8/AQUzf11vEWw1fo94G2c0dfh0zGlYYSf4gCLcBGAsYHQ/w640-h298/text%2Balign%2Bto%2Btop.png "Align text to top of cell")](https://1.bp.blogspot.com/-pc55xSq26yw/X4jRUbETBoI/AAAAAAAARE8/AQUzf11vEWw1fo94G2c0dfh0zGlYYSf4gCLcBGAsYHQ/s1600/text%2Balign%2Bto%2Btop.png)

Align text to the top of the cell  

  

  

  
 I suspect some may not agree with this point, but hey, that's my website and my guide, so...  

  

### **13. Text should be horizontally aligned to the left**

Left alignment is easier to read (assuming it’s not Hebrew or Arabic), so if your cells present chunks of texts - use left alignment.  
  
What. A. Brilliant. Rule.  
You can tweet it, pin it, share it with your closest friends, or just skip to the next one...  
  
  

### **14. Numbers should be horizontally aligned to the right**

(Another strong one - I feel like I'm on fire right now!)  
  
Don’t let your users worry about decimals.  
When it comes to numbers, aligning the text to the right makes it easier to review, compare, and quickly add them up in the head.  
  
  

### **15. Special fields should be horizontally aligned to the middle**

Booleans, dates, phone numbers, and the likes are better aligned to the middle to maintain a consistent structure.  
  
  

### **16. Use consistent string formatting** 

Structured fields like phone number, date, and duration, should all be formatted in a way that will maintain a fixed number of digits (or characters) and provide a consistent experience.  
  
For example, 1/1/19 should be formatted as 01/01/19 to ensure all dates get the same visual weight.  
  
  
Amazing stuff, so basically each field type requires a slightly different approach.  
Here are rules 13-16 combined in one UI snippet:

  

  

[![Use consistent string formatting in your table](https://1.bp.blogspot.com/-wcsw6aQusaM/X4jRzCAUMrI/AAAAAAAARFE/lesNQewgjik_K0aiYTLR7rZzCULW7CSxQCLcBGAsYHQ/w640-h296/string%2Bformatting.png "Use consistent string formatting in your table")](https://1.bp.blogspot.com/-wcsw6aQusaM/X4jRzCAUMrI/AAAAAAAARFE/lesNQewgjik_K0aiYTLR7rZzCULW7CSxQCLcBGAsYHQ/s1600/string%2Bformatting.png)

Make sure your string formats are friendly and consistent  

  

  

  

### **17. Avoid using too many colors**

At a certain point, the users become blind to the colors, so it’s important to use them wisely.  
  

[![Avoid using too many fonts and colors - the complete tables design guide](https://1.bp.blogspot.com/-y2v-7N_2AWk/X4jSUZymTII/AAAAAAAARFQ/ob8qxV5Wpn8zIcmTlXCz3sl2ES-78aOZgCLcBGAsYHQ/w640-h298/avoid%2Btoo%2Bmany%2Bcolors.png "Avoid using too many fonts and colors - the complete tables design guide")](https://1.bp.blogspot.com/-y2v-7N_2AWk/X4jSUZymTII/AAAAAAAARFQ/ob8qxV5Wpn8zIcmTlXCz3sl2ES-78aOZgCLcBGAsYHQ/s1600/avoid%2Btoo%2Bmany%2Bcolors.png)

  

  

1-2 colors should be enough unless it’s a status field in which case the colored cells will belong to one dedicated column which isn't all bad.  
  

### **18. Avoid using too many font styles, or font weights**

Don’t turn your table into a messy war zone with too many colors, font types, and different weights.  
  
1 font type should be enough.  
  
Bold font is only meaningful when it’s used **occasionally**... (👈😉)  
  
Or as my old cat used to say:  

> "if everything is bold, then nothing is…"

  

[![Don't use bold fonts too often](https://1.bp.blogspot.com/-y0AmxhidQOA/X4jSnlyhvUI/AAAAAAAARFY/vtiCnvxGCH8POFE67QNd7Myqa4QrNwSNwCLcBGAsYHQ/w640-h296/avoid%2Bbold.png "Don't use bold fonts too often")](https://1.bp.blogspot.com/-y0AmxhidQOA/X4jSnlyhvUI/AAAAAAAARFY/vtiCnvxGCH8POFE67QNd7Myqa4QrNwSNwCLcBGAsYHQ/s1600/avoid%2Bbold.png)

Avoid using too many font styles  

  

  

  

### **19. Do not bloat your table with too many status icons or buttons** 

Minimize the use of visual signs that may bloat your UI with indigestible content.  
Use mouse hovering to highlight one row at a time along with the relevant action buttons.

  

[![Do not bloat your table with too many status icons or buttons](https://1.bp.blogspot.com/-xCQ05Ma71JU/X4jTZAB0GxI/AAAAAAAARFk/qPYftw4HL1QKaLmuG_Cw7Ae7kDI_QoyVwCLcBGAsYHQ/w640-h296/remove%2Bicons.png "Do not bloat your table with too many status icons or buttons")](https://1.bp.blogspot.com/-xCQ05Ma71JU/X4jTZAB0GxI/AAAAAAAARFk/qPYftw4HL1QKaLmuG_Cw7Ae7kDI_QoyVwCLcBGAsYHQ/s1600/remove%2Bicons.png)

Don't bloat it...

  

  

### **20. Support multiple selections for bulk actions**

If your table involves a lot of editing - users will look for shortcuts.  
One option to deliver quick and easy shortcuts is by allowing multiple selections

  

[![Support multiple selections for bulk actions](https://1.bp.blogspot.com/-jre0r-0YMfs/X4jTunUrmGI/AAAAAAAARFs/gu-t7pRh3808W1atVgHaPkVMI43hi4FhgCLcBGAsYHQ/w640-h298/multiple%2Bselection.png "Support multiple selections for bulk actions")](https://1.bp.blogspot.com/-jre0r-0YMfs/X4jTunUrmGI/AAAAAAAARFs/gu-t7pRh3808W1atVgHaPkVMI43hi4FhgCLcBGAsYHQ/s1600/multiple%2Bselection.png)

In large volumes, bulk actions are extremely needed  

  

  

  
Along with sorting and filters - multiple selections can help users perform bulk actions on multiple objects. Once again - use this capability only if editing is a frequent activity in your product.