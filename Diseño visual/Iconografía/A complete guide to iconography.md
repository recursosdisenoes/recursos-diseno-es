https://www.designsystems.com/iconography-guide/

Icons are a crucial part of any design system or product experience. Icons help us quickly navigate. They are language-independent. And best of all: they're real tiny, so they don't take up very much real estate. Icons are a fundamental part of a good design system and are very helpful for marketing materials. They’re the foundational building block of illustrated content, but they are also highly technical.

There aren't many people who love to design icons, and even fewer who are great at it. I wrote this guide to help you become one of those people.

![Venn-Diagram](https://images.ctfassets.net/7jw9uvgmirvi/74BVyk6RfIQGAJuqlhaOGU/7723f354d17f580cd967150dea6ba0e6/1-Venn-Diagram.png)

Whether you are a design systems expert, an illustrator, or a product designer, this guide will help you learn how to build icons, how to align them with your brand, and how to implement them into your design system. Let's start with the basics.

## Basic elements of an icon

### Size

Consistency is key with icons, and all your icons should be the same size when you build them. First, you'll need to make sure that you know how your grid is built (multiple of 8 or 10?). From there, your base icon size should relate directly to that. So, if you have a grid based on 8s, you'd want to build at 16, 24, or 32.

Choose a common size to build all your icons to, and then allow your engineers to scale to other sizes that might be needed by other designers. You don't want to build the same icon over and over at a multitude of sizes.

When you need glyph complexity, that's when you want to start adding sizes. You might have your base product icon at 24px, but marketing icons at 80px because of the vast difference in use. You'll want to add detail for those larger sizes.

![houses scale](https://images.ctfassets.net/7jw9uvgmirvi/zEFETwJBuwONuwU5GIxrj/98196770c222635ae8895aa8185d03ee/2-houses.png)

Shop icon at 24x24, 40x40, and 80x80

When building the same icon at different sizes, I like to start with the largest size and go down. I find it much easier to remove details and simplify, rather than adding as I go up. It also gives you a sense of the object before you truly minimize it.

### Color

For product icons, use 1 color: black. Anything more than that and your components are going to become too complex and difficult for other designers to leverage. For marketing icons, you might want to use 2 colors if it is a crucial part of your brand, but I personally believe icons should be a single color. Anything with 3 or more colors is an illustration, not an icon.

![Drinks](https://images.ctfassets.net/7jw9uvgmirvi/6ETnUgi2ms9GuoDpUtmU2D/18bc7529fe909b4fe8e673b42906e7fd/3-Drinks.png)

Left: this is a spot illustration. Middle: icon with perspective. Right: flat icon.

### Grids

The **pixel grid** is the fundamental grid that uses the smallest increment: a pixel. When building icons, you always want to align objects to the pixel grid, especially straight lines. But, you can build other shapes on the pixel grid (and if you're using Figma, you already are automatically). You want to build things on the pixel grid, not just because it will render more nicely, but because it makes your life easier. Spacing things evenly is much easier when you're using a grid. It helps you stay consistent with your placement, and overall will make your icons look better. You can easily see in Figma the difference between something being 'on-pixel' and off.

![Group (10)](https://images.ctfassets.net/7jw9uvgmirvi/4FJojSCuwlE2Pdl3Kg6cmh/1fa7c0b270bd9ab15d3f4e7b9cf74d72/Group__10_.png)

Left: On pixel. Right: Off pixel.

I like to build myself a grid before I start. Here are my settings in Figma.

![briefcase with grids](https://images.ctfassets.net/7jw9uvgmirvi/7EEKlGUtPFDc5vMAYIcSrI/aa73b75d9ba26db8b408b8642b158fce/4-Grid.png)

Great! Now that you've mastered the pixel grid you’ll want to learn about the optical grid. The optical grid helps us figure out where the center of mass of the icon is, as well as how large it is perceived by the human eye. Circles and curved objects take up less visual space than squares. It is best to put your icons in a fixed size container so that they’re all identical dimensions when exported. Adding this intrinsic padding supports the optical/perceptive weighting without additional fussing in dev later down the line.

In building my optical grid, I like to give padding at the edge that’s equal to my stroke weight, or possibly double if I'm using a 1px stroke. You can see in the examples below how the different shapes go to the different edges of the grid.

![Group 2 (1)](https://images.ctfassets.net/7jw9uvgmirvi/4C1tVk4XmRFWf4uoF5Lr7t/cd090c180a3d129e3702c07015834971/Group__11_.png)

Visually, the dominant object should be centered both vertically and horizontally.

![case with key](https://images.ctfassets.net/7jw9uvgmirvi/5SesdMsVfSff3MILXkxNHy/d6d66278754502fb5be0743849cec4a0/09-Optical-Grid-05.png)

Dominant object (rectangle) is centered

If you're using the pixel grid and taking advantage of the optical grid, you're going to be streets ahead.

### Strokes and fills

Remember when I said consistency is key? I'm saying it again. Nothing bothers me more than seeing two icons side by side where one is filled while the other is stroked. Making sure your icons are all styled the same way is very important. You might have use cases for applying a fill to show something is selected, for instance, but you definitely want to create a set with one style, and possibly create the other variant.

Typically, filled icons have higher recognizability. Stroked icons give you great ability to create tiny details. When choosing which style is more appropriate, you should also consider your overall brand.

If you're going to create stroked icons, strokes all need to be the same weight. I also recommend that the space between strokes not be thinner than your stroke weight.

![Trash can](https://images.ctfassets.net/7jw9uvgmirvi/3957h6OhfvOzbmUcKybKN1/cb367b073711b2654fe5fb63310797b4/10-Trash.png)

Distance between stokes should reflect stroke weight whenever possible

Maybe you have an icon set that fulfills one style, but not the other. When creating filled versions of stroked icons, you're going to want to look at how you can simplify the line work. Ideally, filled icons are like shadows, rather than inverted line-based icons. Creating stroked versions of filled icons involves determining what stroke weight you can fit in your space and what details you might add while maintaining clarity.

![Icons-Style-Options](https://images.ctfassets.net/7jw9uvgmirvi/X0X9bZhSOlVhC09qo9Bgp/84fb5d83a85fab7630164c283329d470/11-Icons-Style-Options.png)

I do not recommend making stroked icons at smaller than 10px (assuming 1px-2px stroke weight). They will be very hard to decipher.

## Style choices

Your icons are a reflection of your brand. When starting this work, it is important to understand the core values of your brand and how they manifest visually. Some adjectives to think about are hard/soft, casual/formal, luxurious/economical, and literal/abstract. You may have an illustration style you can reference.

Some icons seem like no-brainers (an X, a hamburger menu, a chevron), but these icons require you to have already figured out the basic tenets of your icon system. I recommend starting with harder icons (ie. more complex) to help you determine what rules you want to instill. This way, once you start designing simpler icons, it will be easy breezy.

![Icons-Style-Options-Stroked](https://images.ctfassets.net/7jw9uvgmirvi/74ZdOcDV1wFVseCn3dCkVI/fe476fe00f0f51731f455a58dade72d4/12-Icons-Style-Options-Stroked.png)

5 product icons in 5 styles—note how small differences make each set feel consistent and whole.

Here is a selection of both product and marketing icons that reflect the voice and tone of the company's visual brand:

-   [Uber](https://brand.uber.com/guide#iconography-system-icons)
-   [Google](https://material.io/tools/icons/?style=baseline)
-   [Apple](https://developer.apple.com/design/human-interface-guidelines/ios/icons-and-images/system-icons/)
-   [Airbnb](https://www.zachroszczewski.com/airbnb/)
-   [Square](https://www.bonniekatewolf.com/icon-system.html/)

## Drawing icons

### Geometric shapes

Unless I'm creating a very natural, organic icon style, I like to start with basic shapes to create the forms of my icons. Rectangles, squares, and circles all give you great starting points to create more polished icons.

![13-circle duck](https://images.ctfassets.net/7jw9uvgmirvi/2FIsmwTAMMHgxWMmC5vC7k/cb94a51388524e36f9ccb3778540b792/13-circle_duck.png)

This rubber duck is made of circles (and one rounded rectangle).

When drawing geometric forms, if you need to make complex polygons, you can either start from a square or rectangle, or you can use the pen tool to go from point to on pixel. When doing this, it is extra important to have a clear grid so you can see where those points are going.

When you need to draw **angled geometric shapes**, I do not recommend just using a rectangle and rotating it. Instead, use the pixel grid to draw your angled rectangles.

![14-pencils](https://images.ctfassets.net/7jw9uvgmirvi/4xcuIeBBSspyd4HnFy88qA/9e2f0cca07188d20474d8a9770408ba5/14-pencils.png)

Left: rotated rectangle (anchors do not line up with grid). Right: hand-drawn rectangle (ensures your points line up to the grid).

### Natural forms

Drawing more natural forms in Figma is easy. You can either use the traditional method of drawing curves point by point, or you can use Figma's excellent point corner radius tool. I like to draw all my points as straight lines and then round the corners with the corner radius tool. This tool is very helpful for creating organic, balanced shapes. Because Figma's corners automatically adjust, you can move around those points and the corners will adjust for you.

![15-IconGuide Dog-Points](https://images.ctfassets.net/7jw9uvgmirvi/5MYYSotfaMbGOnhZUgrW1T/9eb43f876de0aaf9305a64be1361d3be/15-IconGuide_Dog-Points.gif)

### Corners/Joins

There are a couple of options for corners: mitered (square), beveled, and rounded. I highly recommend you stick with one style for your icon set.

### Corner radius

When using this for rounding squares and rectangles, you want to make sure all your corners have the same radius. When creating concentric shapes, you'll need to adjust your corner radii to create the perfect concentric shapes. Interior shapes will have a smaller radius than exterior shapes.

![16-briefcase](https://images.ctfassets.net/7jw9uvgmirvi/356XuxbBaWnoankNF8sEhQ/d0b0083dab2feab17e835ff8ca908594/16-briefcase.png)

Great sample of concentric radii in this briefcase

Any intermediate point on a path can be rounded via the Corner Radius property in the Inspector. If you select the entire path, it rounds all corners to the same degree. If you go into Edit mode, you can select individual points and round them separately.

### End Caps

End caps can be rounded or squared. Stick with one option.

### Filled objects

When your icons require filled objects inside their main forms (like a window in a house), you'll ideally want to keep stroked shapes in stroked icons. And filled objects in filled icons. When you don't have space for stroked shapes, you want to use filled shapes that are proportional to your strokes. For instance, if you have a stroke weight of 2px, you don't want filled shapes that are bigger than 4x4px.

### Metaphor

Metaphors are important in icons - we use them all the time without even thinking. An icon of a house means homepage. An insect means an error. When scaling icons to create smaller versions, I like to keep the metaphor I'm using in mind to communicate the icon's message.

![17-metaphor-1](https://images.ctfassets.net/7jw9uvgmirvi/2tQpFsGO6AZZJlct86221W/36896d49b019b341da9c27d505d4a27b/17-metaphor-1.png)

Use a common metaphor to continue at a smaller size as opposed to simply making the exact icon at a smaller scale.

![18-metaphor-2](https://images.ctfassets.net/7jw9uvgmirvi/4uvnyJ9JkWz5RExdjvUElp/03cbcb393a26538d6cb1fa69090c377a/18-metaphor-2.png)

When all the content won’t fit, determine which details are most important and then remove the excess.

![19-metaphor-3](https://images.ctfassets.net/7jw9uvgmirvi/3bICzdNg4RMO57bREnxPKG/0ae8be1699ef407075c36e043600ae6f/19-metaphor-3.png)

If constrained by space, you can simplify crucial details rather than removing them.

### Perspective

Using perspective in icons is tricky - their size makes it difficult since drawing with perspective takes up extra space. If you do want to use perspective, either use it widely and make it a key part of your system, or use it sparingly when it helps increase legibility and clarity.

![20-perspective](https://images.ctfassets.net/7jw9uvgmirvi/7ilXGCJHBNk4SnWb18Gdz/9f4c7b51fb0ade39ce3e373148a62223/20-perspective.png)

Top row: flat. Bottom row: perspective.

### Type (avoid!)

When possible, avoid type in your icons. Icons are meant to be global. If you do need type (for instance, currency symbols), draw it yourself, rather than using a typeface.

## Tool tips

### Boolean Operations

Boolean operations combine any set of shape layers through one of four formulas: Union, Subtract, Intersect, and Exclude. This tool is live, and amazing. It is a great way to make your icons more editable. Rather than having to cut paths, you can use the union feature. Don't want to find the intersection of shapes by hand? Try subtracting.

![21-IconGuide-Boolean](https://images.ctfassets.net/7jw9uvgmirvi/7rES2t3UKk1YpCtBHGcM0M/1ad316d0111830c2a839c3eef5b59301/21-IconGuide-Boolean.gif)

Boolean groups are treated as a single shape layer and share fill and stroke properties and can be combined with other boolean groups through subsequent boolean operations.

-   **Union**: Union combines the selected shapes into a boolean group. If the objects overlap, the new shape’s outer path consists of the composite of its sublayers’ paths minus any segments that overlap. The stroke would then be applied to that outer path ignoring any path segments which overlap each other.
-   **Subtract**: Subtract is the opposite of Union. Subtract removes the area of a shape or set of shapes from a base shape. Only the bottom shape layer is solid, the rest are subtracted from it.
-   **Intersect**: Intersect creates a boolean group whose shape consists only of the overlapping parts of its sublayers.
-   **Exclude**: Exclude is the opposite of Intersect. Exclude shows only the areas of its sublayers that do not overlap.

Once I'm finished with an icon, I like to create a union (if it isn't one big path already), so that when future designers are adjusting the color, it is easy to just change one property (the fill) instead of fills and strokes.

### Vector Network

Vector networks are one of the most unique features in Figma. Most pen tools draw paths in a loop with a defined direction, always wanting to reconnect to their original point. Vector networks do not have a direction and can fork off in different directions without requiring a separate path object to be created. Complex objects can then be created within the same object and with the same properties much faster than they could be drawn using traditional vector path tools. For more on this, visit this [article](https://help.figma.com/article/63-vector-networks/).

## How to use icons in a design system

Making your icon set accessible to the rest of your team is a matter of organization, asset management, and awareness.

### Organization

Let's start with file naming. Your icons should be named based on what they show, not what they represent. For instance, a stopwatch icon should be named **stopwatch**, not **speed**. A lightbulb should be called **lightbulb**, not **idea**. You want to make instantly clear to people what the icon is, not what it communicates on a more conceptual level. Shorter names are better, too. When you need multiple words, use a dash to separate them.

![22-chefhat](https://images.ctfassets.net/7jw9uvgmirvi/6HuptcBmkIAVFLw7SgjOTl/87f01b1b03113f04005582aa9d9f333e/22-chefhat.png)

Icons like this might need multiple words—for instance, chef-hat.

Eventually, you’ll turn all your icons into components. In Figma, components works just like frames, with the twist that duplicates of a component create new instances rather than copies. This means you can have a giant library of all your icons and when you need to use one, you create an instance from the library. If someone makes changes to the original, your icons will still be up to date. You can search these assets, so you may want to add information that is searchable. But rather than putting it in the file name, there is an alternative. Figma has a component description box which allows you to add tags and keywords. This is a great place to add all those phrases people might be searching for in your library without making crazy long, complex names. This is where those product values go!

To help your engineers, you'll want to make use of both frames and pages. Pages represent the outermost grouping (so I like to sort those by size). Frames then help you narrow your content, as in the example below. This icon's naming system goes **size > category > file name**.

![23-Organization](https://images.ctfassets.net/7jw9uvgmirvi/2a7L868vPrKE0KRocEIsEu/c3b23ca132f34563338e12d21d266f42/23-Organization.png)

When you have the same icon with variants, here's how I like to handle them.

**Different sizes**: Use different pages since you will rarely be switching directly from one instance to another.

**Filled vs. stroked**: If you are using both styles, use a slash after the icon name to indicate filled or stroked icons.

![24-Coffees](https://images.ctfassets.net/7jw9uvgmirvi/394n4HE2amAjQnTPB7PIlJ/3b77a4bab3377868e44502f181f3f9f1/24-Coffees.png)

Left: coffee/stroked. Right: coffee/filled

**Adjusted imagery**: When you have an icon with a visual variant (for example, multiple currency variants), you can also use naming to help differentiate, using the same method as filled vs stroked icons.

![25-Shields](https://images.ctfassets.net/7jw9uvgmirvi/5KugjMk9FempnsFYYdyvZF/5e587a79affe7294ca488834c9a3c777/25-Shields.png)

Original icon on left would be 'shield'. Then, left to right, 'shield/dollar', 'shield/euro', 'shield/pound', 'shield/yen', 'shield/plus'

### Managing your assets

Once you're done with your icons, you want them to be as clean as possible for the best possible export. Use boolean operations to simplify your work (remember our friend Union?). Avoid any extra lines or shapes. Check that all your lines fall inside your frame. It is absolutely worth having another person look at all your icons and double check for tidiness.

Figma is great because it encourages collaboration and transparency. With icons, it can be tempting to allow all your designers to have edit access so they can add new icons. I recommend collecting icons individually, auditing them, and adding them yourself when they are up to standard. Giving your colleagues view access (and access to your library) is enough to get them involved in what you're making without ending up with a cattywampus library and file. Some of your colleagues may want to create different versions of the same icon (in different colors or with different names, for instance). This will often happen when someone associates an icon with a concept or product. You never want to have more than one version of each icon in your library. Use the component description for those names. Your fellow designers should be adjusting icon colors in their individual files, not in the master. Believe me, you'll have to make changes to these icons from time to time and you don't want to do it in more than one place. File formats are key for when you're ready to export icons. If you're providing icons to partners outside of your design or engineering team, you're probably giving them .png files. Export at 1x, 2x, and 3x to suit multiple devices. For engineering and design, you'll often be exporting .svg files which are editable in design programs and are drawn in the browser through code when rendered online on your app or site. When exporting SVGs, you'll want the cleanest possible code. Another great reason for choosing Figma is the hyper minimal SVG exporting. Because they are optimized, it removes the need for further optimization down the line. Check out this [article](https://www.figma.com/blog/with-figmas-new-svg-exports-less-more/) to learn more.

### Getting your icons into the hands of others

You can be the world's greatest icon designer, but if you can't get your icons implemented in your app/webpage/direct mailer, it won't do any good. Before you start designing, talk to the engineering team responsible for getting these into product. They will be able to give you information about the website or app infrastructure which will drive some of your choices, like stroke weight or size. Ask other designers what has been done in the past to make sure you're not duplicating work. Figure out from your PMMs what additional icons they have been yearning to see. Be the friendly coworker who asks people for feedback, advice, and help. It will give you a better idea of what you should be making, so you aren't redoing work, or ignoring key tenants other people already figured out. And when you're ready to implement with your developers, try [using Figma’s API to programmatically export](https://johanronsse.be/2018/09/23/the-figma-api-for-the-rest-of-us/).