Programming in the Real World
- Introduction: Frameworks and Libraries

When using a Library we're in charge and we decide when we call it.
When using a Framework its in charge and it decides when call us.

drawPixel(10,10)

func drawLine()
    for i in 10...30
        drawPixel(i,10)
    end for
end func

// call it
drawLine()

// calls drawSquare()
  // calls drawCube()
    // call drawSpinningCube()

Generic Functionality (it is a library)
    - "Standard Library"
    - Date and Time Functions
    - Sorting Functions
    - Searching Functions
    - String Manipulation

Library / Module
    import or include module
    from JSON import JSON

General
    Date / Time functions
    Math functions
    File Input/Output
    Error Handling
    Mulithreading
    Collections
    (etc.)

Specialized
    Audio library
    2D Graphics library
    3D Graphics library
    Wed / HTML library
    Encryption library

- What is an SDK? 
    software development kit
    some SDK's these days will come when you install and app
    others will include the app when you download the SDK

- What is an API?
    Application Programming Interface
    work out where you are supposed to interact with it
    Electrical the electrical box that is an interface
    we use the user interface on our phones
    yet we want to know the how interact with the API.

--------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------

Using an API (Pseudocode)

Import someCompressionLibrary

// TODO: compress image? how? idea below to get us thinking

var myCompressor = new Compressor()
myCompressor.setInput(myImageFile)
myCompressor.setOutputName("output.zip")
int result = myCompressor.zip()
if result > 0 {
    //something went wrong....
}

hope that API is well documented and up to date.
This saves us from having to reinvent the wheel.

--------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------

- Choosing a Programming Language

Software Development Areas
what are you interested in building

Game Development
    Unity (C#)
    Unreal Engine (C++)

Web Development
    Ruby on Rails
    ASP.NET (C#)
    Angular JS (JavaScript)

Mobile Development
    iOS (Swift) (xCode)
    Android (Java) (androidStudio)

Enterprise Applications
    Java
    C# (vscode)
    VB.NET

Data Visualization
    Python
    R

Figure out what to do first

Suggestions from Plural Sight
Python - if rule both out python
Swift - apple hardware
JavaScript - websites

Simon Allardice