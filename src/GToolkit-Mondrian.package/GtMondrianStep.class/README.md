I am a utility class that holds the state about the current step in the Mondrian view creation. I am particularly useful in the case of constructs like ==nodes:forEach:== which creates  a nested step. For example, in this case, the ==shape== should describe the scope inside the step and not be applicable in the broader scope.