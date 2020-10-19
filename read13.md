# The past, present and future of local storage for web applications:

    - THe operating system provides an abstracion layer for storing the getting applications data. Values could be stored in the registy, ini files, xml files or some other place. 
    - User data allows web pages to store up to 64kb of data per domain. This was during the internet explorar which was the first web browser that everyone knew. There are many other webpages that came out during the era and many of them failed. 

## HTML5 Storage
    - HTML5 Storage is a specification named web storage. 
    - Certain browsers vendors also called local store or dom storage. 
### HTML 5 Storage support:
    - IE 8.0+
    - FireFox 3.5+
    - Safari 4.0+
    - Chrome 4.0+
    - Opera 10.5+
    - Iphone 2.0+
    - Andriod 2.0+
    To check for HTML 5 store we would use :

        function supports_html5_storage() {
    try {
    return 'localStorage' in window && window['localStorage'] !== null;
    } catch (e) {
    return false;
    }

## Using Storage:
    - HTML5 storage is based on a named key value pairs. You store data based on a key, that then you can retrice the data with the same key. The named key is basically a string. 
    - If we are storing and retreiving anything other than string we would use functions like parseInt() or parseFloat(). 
    - There are ways of removing the value for a given named key and clearing the store we would use : 
            interface Storage {
    deleter void removeItem(in DOMString key);
         void clear();
    };

## Tracking changes to the HTML5 Stoarage Area:
    - You can use storage event to keep track progammatically of when storage areas changes. 
    - The storage even is supported everyywhere in the localStorage obejct which is supported. 

    PROPERTY	TYPE	DESCRIPTION:
    key	string	the named key that was added, removed, or modified.
    oldValue	any	the previous value (now overwritten), or null if a new item was added.
    newValue	any	the new value, or null if an item was removed.
    url*	string	the page which called a method that triggered this change. 

## Beyond named key value pairs: 
    - A new api has been standardized and implemented across all major browsers, platforms and devices. 
