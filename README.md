# InterviewQuestionsforWEB_DEV

20. How do you prevent an object to extend
    The Object.preventExtensions() method prevents new properties from ever being added to an object (i.e. prevents future extensions to the object). It also prevents     the object's prototype from being re-assigned.
    const object1 = {};

    Object.preventExtensions(object1);
