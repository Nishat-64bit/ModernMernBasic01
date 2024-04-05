          -------------------------------------------------------------------
          recap Arithmatic operator  <Start>
          -------------------------------------------------------------------
          variable : let , conts , var 
          data type : primitive , non-primitive 
          primitive : string , number , boolean , null , undefined 
          non primitive : array , object , function 
          ////

            let a = 30;
            let b = 40;

            let sum = a + b;
            console.log("the sum is ", sum); // the sum is  70

            let X = "30";
            let Y = 40;

            let sums = X + Y;
            console.log("the sum is ", sums);
            //  the sum is  3040
            // 1st e string paise porer ta ke string banaite pare nai , tai se tar pase bose gese ,
            // keal korbe 3040 sada color mane pura tai ekon string , tobe se sudu + er khetre erokom ta kore ,
            // baki operator er janno ta kore na

            let p = "30";
            let q = 40;

            let minus = p - q; // let minus = p - q; // ekane equal holo operator , minus,p,q holo operand ,
            console.log("the minus is ", minus); // the minus is  -10


            let u = 5;
            let i = 2;
            console.log("the exponential is", u ** i);// the exponential is 25
            console.log("the exponential is", u ** 2 ); // the exponential is 25


            // know about Arithmatic operation like addition , substraction , multiplication , divide ,            Modulas (bagses) from w3 school ..

            // lets talk about pre-increment  // we will discuss post-increment in loop 

            let o = 5;
            let increment = ++o // pre incre // aage thekle pre// ekta kore value se add korbe // pore thakle post //
            console.log("The increment is ", increment); // The increment is  6

            let r = 5;
            let increments = ++r 
            console.log("The increment is ", ++increments); // The increment is  7 // ek ek kore varce 

            let s = 5;
            ++s ;
            let incrementss = s // s er value 6 hoice seta incrementss er bitore save hoice
            console.log("The increment is ", incrementss); // The increment is  6//

            // same as pre-decrement /// 

            let Q = 11;
            let decrement = --Q  // value 10
            console.log("The decrement is ", --decrement);// value 9 // The decrement  is  9  // ek ek kore komce

          -------------------------------------------------------------------
          recap Arithmatic operator <End>
          -------------------------------------------------------------------
          ----------------------------------------------------------------------------------
          recap Assignment operator & logical operator & if-else & voting application <Start>
          ----------------------------------------------------------------------------------
          // //

            // let x = 5;
            // x = x+5; // reasign
            // console.log("the reassignment is", x); //the reassignment is 10

            // let p = 5;
            // p = p+5; // reasign // 10
            // p+=10 // p = p + 10  // 20
            // console.log("the reassignment is", p); //the reassignment is 20

            /// check minus aassignmet 
            // p-=5 

            /// check multiply aassignmet 
            // p*=5 

            /// check divide aassignmet 
            // p/=5 

            /// check module aassignmet 
            // p%=5 

            // check exponential operator assignemnt
            // p**=5

            // ----------------- Logical Assigment operator -----------------------
            // three types : && , || , !

            // And operator e 2ta true hoile output true hobe 
            // true && true = true 
            // true && false = false

            // or operator e 1ta true hoile output true hobe 
            // true || true = true 
            // true || false = true

            // !true = false 
            // !false = true 

            // ----------------- Greater than / less than operator -----------------------
            // let j = 50;
            // let h = 40;

            let k = 50;
            console.log(k > 40); // true asve

            let k = 50;
            console.log(!k > 40); // false asve

            // console.log(j>90); // false
            // console.log(j>=90); // false
            // console.log(h<90); // true
            // console.log(j<=50); // true
            // console.log(j<=50); // true
            // console.log(!h<=50); // false
            // console.log(!j<=50); // false

            // ----------------- Conditional Statement -----------------------

            //   if (condition){           ----- if holo keyword // () parentthesis ke bole boe >>> boolean context 
                // excution body if true
            //   }else{
            //   excution body false hole 
            //   }

            /// Example : 01

            // let G = 50 ;
            // let H = 90;

            // if (G>H){
            //     console.log("G is actually greater than H");
            // }else{
            //     console.log("g is less than h");
            // }/// output : g is less than h

            // let Y = 50;
            // let Z = 50;

            // if (Y>Z || Y >= Z) { // 1ta logic true hoile e hoice  false || true = true 
            //     console.log("yes it is ");
            // } else {
            //     console.log("this is not equal");
            // }/// output : yes it is


            // ----------------- voting application -----------------------
            //let age = prompt("Enter you age ")
            //console.log(typeof age); // ja dibe tai se string korbe prompt er bitor 
            //console.log(typeof +age); // number e convert korte ciele use +variable name

            // ----------------- voting application start-----------------------
            let input = prompt("Enter Your age")
            let ageInput = +input // u can also use number instead of usig +   // console.log(Number input)
            /**
            * jodi 130 er besi hoi tabe , moire jaw
            * jodi 81 theke 130 er choto hoi tobe , dadu bari jaw , vote ami dibo tomarta\
            * 18er equal and 80 porjonto hoi taile perfect age for voting
            * jodi 18 er kom and 0 theke besi tobe under age , basai ja
            * jodi negative value kew dai tobe - wrong input
            * jodi kew string input kore tobe invaild
            * 
            */
            if (ageInput >= 130) {
                console.log("moire jaw");
            } else if(ageInput>=81 && ageInput <130){
                console.log(" dadu bari jaw , vote ami dibo tomarta");
            }else if (ageInput >=18 && ageInput <=80 ){
                console.log("perfect Age for voting");
            }else if (ageInput >=0 && ageInput <18 ){
                console.log("under age");
            }else if(ageInput <0) {
            console.log("wrong number");
            }
            else{
                console.log("invaild syntax");
            }
            // ----------------- voting application End-----------------------

            /**
            * Multi line comment use korete 
            * just ekta backslas / then 2ta star den 
            * then dekben automatic arekta star and backslash asve 
            * then sudu joto line lagbe nice naman enter press kore
            */

            /**
            * Use camecase and underscore for varaibleNaming
            */


          ----------------------------------------------------------------------------------
          recap Assignment operator & logical operator & if-else & voting application <End>
          ----------------------------------------------------------------------------------
