NSArray-firstObject
===================

NSArray category with firstObject

NOTE: If you're building for iOS 7+, firstObject has been added to the SDK and this category is not needed.

Pretty plain and simple but gets rid of the need to call "objectAtIndex:0" just to get the first object in an array.

To use this category, drag and drop NSArray+firstObject.h and NSArray+firstObject.m into your project. #import NSArray+firstObject.h into your view controller and your done.

Here's an example of how to use this in your code:

Before

  ```objective-c  NSString *newString = [myArray objectAtIndex:0]; ```

After

  ```objective-c  NSString *newString = [myArray firstObject];```
 





This code contains no copyright and can be freely used for anything you want personal, commercial, etc..

This software contains ABSOLUTELY NO WARRANTY either expressed or implied.
