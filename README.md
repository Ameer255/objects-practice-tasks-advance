# objects-practice-tasks-advance

# Advance level tasks


// LEVEL #3 ADVANCED TASKS

// Recipe task

const recipe ={
    title : "Briyani",
    servings: 20,
    ingredients: ["rice", "onion", "tomato"]
}

console.log("Recipe name : "+recipe.title);
console.log("Servings : "+recipe.servings);
console.log("Ingredients : ");

recipe.ingredients.forEach(i=>{
    console.log(i);
});



// Reading list task

const book1 = {
    title : "Sophies world",
    author : "justin gaarder",
    isRead : true
};

const book2 = {
    title : "HTML & CSS",
    author : "Andy harris",
    isRead : true
};

const book3 = {
    title : "The east",
    author : "bertrend russel",
    isRead : false
};

let readingList=[book1, book2, book3];

readingList.forEach(book=>{
    console.log("Book : "+book.title);
    console.log("Author : "+book.author);
    
    if(book.isRead){
        console.log("Status : "+book.title+" by "+book.author+" is already read..!!\n");
    }
    else {
    console.log("Status : "+book.title+" by "+book.author+" needs to be read.!!\n");
        
    }
    
});
