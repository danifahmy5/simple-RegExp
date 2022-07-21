////////////////////////////////////////////
// javascript regular exprestion 
///////////////////////////////////////////
var string = 'Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus.'

let find = 'magna'
const regExp =  new RegExp(find,'i')

let test = regExp.test(string);
//output = boolean : true
let exec = regExp.exec(string);

//output = array : [ 
//     'magna',
//     index: 8,
//     input: 'Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus.',
//     groups: undefined 
// ]

let search = string.search(regExp);
// output = index : 8
let replace = string.replace('magna','*custom your string*')
// output = string :  Vivamus *custom your string* justo, lacinia eget consectetur sed, convallis at tellus. 

/////////////////////
// hightlight string
/////////////////////      
 let hightlight = string.substring(0,search) + '<b>' + string.substring(search,search + find.length) + '</b>'  + string.substring(search+find.length)
//  output = string : Vivamus <b>magna</b> justo, lacinia eget consectetur sed, convallis at tellus. 
