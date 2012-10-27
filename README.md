NSArray-firstObject
===================

NSArray category with firstObject

Pretty plain and simple but gets rid of the need to call "objectAtIndex:0" just to get the first object in an array.

To use this category, drag and drop NSArray+firstObject.h and NSArray+firstObject.m into your project. #import NSArray+firstObject.h into your view controller and your done.

Here's an example of how to use this in your code:

    NSArray *myArray = [[NSArray alloc] init];
    NSString *newString = [myArray firstObject];
 





This code contains no copyright and can be freely used for anything you want personal, commercial, etc..

This software contains ABSOLUTELY NO WARRANTY either expressed or implied.