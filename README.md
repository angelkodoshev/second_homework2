   # second_homework2defmodule Homework do

       def first_task() do
       # Using a pattern match, assign "Alice" to a variable "first_name", and "Addison" to variable "last_name"
 

       first_name="Alice"
       last_name="Addison"
       tuple={first_name,last_name}
       _ = {"Alice", "Addison"}



    # Assign the number to the variable "age", and the letter to "sex"


    age=32
    sex="f"
    tuple={age,sex}
    _ = {32, "f"}



    # Create a patter, that will fail if the first item of the tuple is anything other than "200"
    
     x=200
     string="example data"
     atom=:an_atom
     tuple={y,string,atom}//error
     tuple={x,string,atom}
     _ = {200, "example data", :an_atom}


    # From here on, do not use variables. All of these are heavily inspired by elixirkoans
    true_ = true

    false_ = !true

    2 = 1 + 1 _

    4.0 = 2 / _ -> 4.0=8_/2

    6 = 2 * 3 _

    3 > 1_

    "hello world" = "hello"_ <> "world"
    
    _tuple = [1, 2] ++ [:a, "b"]
    [1,2,:a,"b"]


    list_ = [1, 2, 3] -- [3]
    [1,2]

     end
  
     end
