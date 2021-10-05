### Welcome to Yani's page

Hello there. My name is Yani Garcia. This is an in progress web page as I try to determine what is best suited to the web page as opposed to simply copy and pasting my resume.


### About Me

I prefer the name Yani because it is easier to pronounce and remember for most people. I learned how to ride a motorcycle when I was younger because I thought it looked cool and I wanted to get one instead of a car. I enjoy cooking new recipes that I find off of the internet and spicy food.

As of Fall 2021, I am interning at MGHPCC and I hope to learn more the longer I am here. I have partially written a program to calculate values and update it in a database to handle some repetative work.

### Python programming example
Below is a program I threw together to calculate different parts of a right trangle assuming the user knows the lengths of two sides.

```
#calculate the missing value for a right triangle
#programming reminder that c^2=b^2+a^2
#Also import math
import math

ans=input("Are you looking for a leg or the hypotenuse? Enter l for leg or h for hypotenuse");

while ans!=0:
    if ans == "l":
        numb=input("Enter the length of the other leg ");
        try:
            b = int(numb)
        except ValueError:
            print ("That is not a number")
        numc=input("Enter the length of the hypotenuse ");
        try:
            c = int(numc)
        except ValueError:
            print ("That is not a number")

        a=math.sqrt(c*c-b*b)
        print("The missing leg is {:.2f}".format(a));
        break;

    elif ans == "h":
        numa=input("Enter the length of the first leg ");
        try:
            a = int(numa)
        except ValueError:
            print ("That is not a number")
        numk=input("Enter the length of the other leg ");
        try:
            k = int(numk)
        except ValueError:
            print ("That is not a number")

        c=math.sqrt(a*a+k*k)
        print("The hypotenuse is {:.2f}".format(c));
        break;

    else:
        input("That response is invalid.")
        break;
 ```



### Volunteer Experience

Star Catchers, Mercy Medical Center (2010-2012)


-Create exit packages for patients

-deliver meal trays

-answer call bells




### Contact

For future use the web page itself can be accessed [here](https://github.com/TechSQYani/yani.github.io/settings/pages). Yes this links to itself.

