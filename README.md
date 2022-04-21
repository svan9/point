``` pascal
say "Hello, world!\n". // usual string whose print something to console 

true >> say "test is complite\n"?  // usual if construction

cycle1$ // cycle whose named cycle1

    var == other_var >> break cycle1? // condition of cycle => if var equal other_var then cycle1 will been broken

end // end of this cycle

cycle2$ // cycle whose named cycle2

    var == other_var >> break this? // condition if cycle => if var equal other_var then <this cycle> will been broken
    
end // end of this cycle

some_func *args! // creates, names and get arguments function

    say "This function is worked". // usual string

    say *args + " is getting too". // still usual string but with operator plus

end // end of function

some_func. // call function higher


```
