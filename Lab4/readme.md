## Matthew Mosinski October 20th, 2021

## Executive Summary 
  Data, information, and knowledge are often misunderstood and used interchangeably, however; they are very much so different from on another. Data is the details or facts and can be quantitative or qualitative. Information is data that is processed that has relevance and purpose. Knowledge is the human perception or analysis of the data. The final step in the process is wisdom, which is where we now have a deeper understanding of the topic. Data is growing at a rate that is becoming difficult for agencies to manage. This data is referred to as big data. Databases are where data is stored and organized for use. It is important to limit irrelevant and redundant data. Data should be consistent and should be able to deliver the full scope of the story. Data missing key details is data that lacks integrity. 
  Relational databases are the most commonly used types of databases. All data is relational database is related to each and organized into tables. Database management systems (DBMS) are applications helpful in organizing databases. DBMS can be used by one person or multiple people within an organization. Data warehouses take data and organizes it for analysis. Data mining has become a popular practice that looks for patterns and relationships in large data sets. Businesses use these tools and processes to gain an advantage over competition.


## Python IDLE
  The python shell allows you to execute python commands one a time and shows you the results instantly vs. the file editor which allows you to write programs to the fullest. The shell has the “>>>” prompt vs. the file editor which does not.
  
## Code Examples
### Variable:
  A variable is where you store a value, as if it is a box in the computer’s memory. Like in math how x is a variable that represents an integer. X is the variable The author uses spam, eggs, and bacon as variable to stores values. For example:
>>>spam = 10
>>>spam
10
>>>eggs = 5
>>>eggs
5
>>>spam + egg = bacon
>>>bacon
15

### Assignment statement:
  An assignment statement is how you store values into variable. In the example spam = 10, the variable is spam, and the assignment statement is = 10. A variable name is a must for the assignment operator to assign a value to the variable. Assignment statements are useless without variables.
  
### Function:
A function is basically a command. Programmers use functions to achieve a desired outcome. Print, int, str, input, float, etc. are all examples of possible functions that a programmer could use when writing a Python code. There are many different functions that can be used. Similarly to writing a function is excel, () are necessary after the function term in. For example:
>>>print()
		#it is possible to print a blank line
>>>print(‘Matthew Mosinski’)
Matthew Mosinski	#The output is Matthew Mosinski, the function is print.

### Three data types:
The three data types used by the author are string, float, and integer. 
  A string is character that are enclosed in single quotations. For example:
>>>print(‘Hello, my name is Matthew Mosinski’)
 “Hello, my name is Matthew Mosinski” is the string
#Double quotes can also be used to create a sting, multiple double or single quotes can be used
The string command will output the integer as a string, the way it was originally entered in the function. For example:
>>>str(10)
	‘10’
>>>str22.22
	‘22.22’

  A float() function converts all whole number to point float number. Strings can be used within the float function. For example:
>>>float(10)
	10.0
>>>float(‘30’)
	30.0

  An integer is a whole number. If you place a string in an integer function it will return an error. The int() function is also useful if you need to round a floating-point number down. If you want to round a floating-point number up, just add 1 to it afterward. 
>>> int('42')
42
>>> int('-99')
-99
>>> int(1.25)
1
>>> int(1.99) + 1
2

## Graphics

### Raster vs. Vector Graphics
  Raster images are images that become distorted when enlarged from the original image. This is because they are made up of tiny pixels and as you enlarge the image you can see the pixels more clearly rather than the image as a whole or what the pixels are creating. Real life images or images taken with a camera are raster images. Cameras and screen display images using pixels which is why when you enlarge the picture you can see the different pixels more clearly. This distorts the image to the viewer. The more pixels a camera or screen has, the more enlarged an image can be without seeing difference in pixels or any distortion.
  Vector images are geometric designs that are more complex than pixels. The are computer generated graphics that can be enlarged without distortion or pixilation. However, these images are not as practical as raster images in a professional setting. Vector images are more cartoonish.

### Lossless vs. Lossy Compression
  Lossless compression is ideal for simple graphics. Compressed images will be the same closer to their original without an abundance of data loss or data manipulation. Deflate is a lossless compression method commonly used with PNG images and in ZIP and gzip compression. Lempel-Ziv-Welch is a lossless compression algorithm that performs a limited analysis of data.
  Lossy is inversely related to lossless. This is where the programmer will have to choose which data is most important in the image and which data is least important. This could result to color alteration (color averaging) of an image to create smaller files. Programmers typically alter colors rather than brightness because the human eye perceives changes in brightness more than changes in color. These concepts are transform encoding and chroma(color) subsampling. Lossy combined with deflate method of compression can produce almost an identical image to the original.
  These methods matter to programmers because when images are placed into a project, it is important to consider the size of the image. Knowing how to alter the image with the least amount of distortion is imperative.

### File Formats
  JPEG (Joint Photographic Experts Group) is an image format that uses lossy compression to create smaller file sizes. One of JPEG’s big advantages is that it allows the designer to fine-tune the amount of compression used. This results in better image quality when used correctly while also resulting in the smallest reasonable file size. Because JPEG uses lossy compression, images saved in this format are prone to “artifacting,” where you can see pixelization and strange halos around certain sections of an image. These are most common in areas of an image where there’s a sharp contrast between colors. Generally, the more contrast in an image, the higher quality the image needs to be saved at to result in a decent-looking final image.
  GIF stands for Graphics Interchange Format, and is a bitmap image format introduced in 1987 by CompuServe. It supports up to 8 bits per pixel, meaning that an image can have up to 256 distinct RGB colors. One of the biggest advantages to the GIF format is that it allows for animated images, something neither of the other formats mentioned here allow.
  PNG (Portable Network Graphics) is another bitmapped image format that uses lossless data compression and was created to replace the GIF image format. The PNG format was largely unsupported by Internet Explorer for a long time, making it less commonly used than GIF and JPEG formats, though it’s now supported properly by every major browser. PNG files support palette-based color (either 24-bit RGB or 32-bit RGBA), greyscale, RGBA and RGB color spaces. One of PNG’s biggest advantages is that it supports a number of transparency options, including alpha channel transparency.
  All three file types are capable of being compressed, however only PNG and Gif files are capable of lossless compression, whereas jpg is capable of lossy compression.  All three file types are raster images, but only gif and png files are capable of animation. All three file types are commonly used for web design. gif files are typically the smallest of the three in terms of size, however, is the unfavorable choice when it comes to retaining graphics. Clip are is an example of a gif file type.

### File Properties
  In the files properties window, you can find an abundance of information regarding the selected file, such as the date it was created, the size, the location, etc. My logo file is 4.18 KB. This is a small file. It is an SVG file that opens with Google chrome. The path for the file is C:\IT1025MatthewMosinski\images. This is where I saved the file after I downloaded it. This is also the folder that we created earlier in this lesson.
  
## Conclusion
  Human interaction gives databases purpose. Data is entered and processed into information. The information is given to humans as knowledge and used advantageously. It is important to keep data bases organized and maintain their integrity.
	Python is code written in simple syntax that closes resembles the English language. This lesson was a great introduction to python and learning some of the different functions that programmers use.
	When using images or graphics in a project and/or design, it is important to consider the type of image it is, the size of the image, and the type of file the image is saved as. All of these factors will affect the quality of the image. The file format is important when deciding where the image will be used and how it will affect the program and/or website.
