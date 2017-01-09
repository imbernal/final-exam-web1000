#Final exam

1. What are the four steps of mergesort?

//Answer
Steps:
1)If the length of the list is one, it's already ordered
2)Divide the list in 2 parts approximately on half
3)Order the two list recursively using merge order method(taking the less value between two list )
4)merge the list

2. Using JavaScript, generate a random number between 1 and 10.

//Answer
Math.floor(Math.random() * 10 + 1 );

3. Using Javascript, generate a random number between -10 and 10.
//Answer
Math.floor(Math.random() * (20) - 10);

4. Write a coin flip function. It should return the string "heads" half the time and the string "butts" the other half
//Answer
  function coinFlip(){
    var num = Math.floor(Math.random() * 2 +1);


    return num==1 ? "heads" : "butts"

  }

5. Re-state the following expression without using negation:
  !(10 > x)

  //Answer
  (10 < x)

6. Re-state the following expression without using negation:
  !(x && y)

  //Answer
  (x || y)

7. Re-state the following expression without using negation:
  !(x || y)
  //Answer
  (x && y)

8. What is an Angular directive?
//Answer
Angular directive is a html custom tag.

9. When defining an angular directive, you write a function which must return an object called:  
  a. Directive Constructor  
  b. Fidel y Chavez Object  
  c. Directive Definition object  
  d. Directive Object

  //Answer
  d.Directive Object

10. Name 3 of the properties which this object will usually contain.

//Answer
1.restric
2.templateUrl
3.scope

11. In order to send ajax requests in Angular, the most accepted convention is to create an angular:  
  a. Module    
  b. Service  
  c. Controller  
  d. $http
  //Answer
  b.Service

12. Write a function which, given a 2-d array of strings, returns the concatenation of all the strings.
  function twodconcat(arr){

    var test = "";

    for(var i = 0 ; i < arr.length ; i++){
      for(var j = 0 ; j < arr.length ; j++)
        test+=arr[i][j];
    }
  }

13. Write a function which, given a 2-d array and another value x, returns true if x is present in the two d array, and false otherwise.
  function containsElement(arr, x){
    for(var i = 0 ; i < arr.length ; i++){
      for(var j = 0 ; j < arr.length ; j++)
        if(arr[i][j] == x)
          return true;
    }
    return false;
  }


14. What is the relationship between html, the $scope construct, and angular expressions? (Expressions are the ones that are written like so: {{quote}} ).

Scope is a binding between HTML and Angular controller , and using expressions i can put my scope information inside the DOM.
