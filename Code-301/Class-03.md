# Class-03 Reading Notes

## List and Keys

> 1. ***What does .map() return?***
> Map returns a new array from the following array with what ever specifications you want to change in each value.
> 2. ***If I want to loop through an array and display each value in JSX, how do I do that in React?***
> I'm guessing you would want a list of the values form the index so you would do this.
>  const elements = {
   theAvatar: [water,fire,earth,air]
   };
>  function elementList(props){
>     const elements = props.theAvatar
    const elementList =  elements.map(v => <li key= {elements.tostring()}>{elements}</li>);
     return {
        <ul>{elementList}</ul>
     }
}
> 3. ***Each list item needs a unique _key___.***
>
> 4. ***What is the purpose of a key?***
>  Keys help keep track of what has been changed or added or removed in React imagine if you wanted to remove a item without a assigned key one im guessing the code would would break but remember computers are like very very smart 1 year old if you give them direction you have to be specific for what that item is. common practice is to use the .tostring() method to assign keys and if not that id's for the content but if all else fails just use the index  (key = {elements.id}) (key = {index})

## The Spread Operator

> 1. ***What is the spread operator?***
> the spread operator takes in a iterable data type like a array or a string and spread it out so you can use those elements to put in function calls as arguments or whatever else you'd want.
> 2. ***List 4 things that the spread operator can do.***
> 1.you could use it to make a longer array.
> ex.
> const theAvatar = [ water,fire,earth,air ];
> const theNewAvatar = [ ...theAvatar,energy ];
>
> 2 you could use it to spread a array into arguments for a function
>
> ex.
> function AvatarDoTheThing(w,f,e,a){
> return w+f+e+a;
> }
> const bending = AvatarDoTheThing(...theNewAvatar);
>
> 3 you can copy a array
>
> ex
> const aang = [...theAvatar ];
>
> 4 you can use them to make new objects
>
> ex.
> const originalTeamAvatar = {aang,toph,sokka,katara};
> const nextTeamAvatar = {korra,asami,bolin,mako};
> const avatarCharacters = {...originalTeamAvatar,...nextTeamAvatar};
> 3. ***Give an example of using the spread operator to combine two arrays.***
> const myArr = [ ...aang,...theAvatar ]
> 4. ***Give an example of using the spread operator to add a new item to an array.***
> const theAvatar = [ water,fire,earth,air ];
> const theNewAvatar = [ ...theAvatar,energy ];
> 5. ***Give an example of using the spread operator to combine two objects into one.***
> const originalTeamAvatar = {aang,toph,sokka,katara};
> const nextTeamAvatar = {korra,asami,bolin,mako};
> const avatarCharacters = {...originalTeamAvatar,...nextTeamAvatar};

## How to Pass Functions Between Components

> 1. ***In the video, what is the first step that the developer does to pass functions between components?***
>  he declared it in the  component class so that it could change that state when it was called in a child component.
> 2. ***In your own words, what does the increment function do?***
> it adds a count and added updated banner from another component changing the parents state
> 3. ***How can you pass a method from a parent component into a child component?***
> you want to put in the render going into the the child.like any other prop
> 4. ***How does the child component invoke a method that was passed to it from a parent component?***
> he uses the props to call it from the parent like so this.props.increment in the increment event listener in the next component.

## Things I want to know about

1 thought we couldn't use ++ operator in React at all but i saw him doing it is there only specific times we can do that?