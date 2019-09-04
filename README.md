# Loading View
<img src="https://github.com/Wassmd/LoadingView/blob/master/loadingView.png">

`LoadingView.swift` - A lightweight simpile reusable Loading view in swift

This can be used to show loading activity with spinner. 

This can be used in any view controller or add to any view
 
This class can be further customized to give fancy UI touch

<img src="https://github.com/Wassmd/LoadingView/blob/master/sample.png" width="375" height= "600">

Below code show how to use in View Controller

        let loadingView = LoadingView()
        view.addSubview(loadingView)
        
        loadingView.show()
        
When no more need just hide it

     loadingView.hide() 
     
Add constraints in main view or you can place in center by calling

 `loadingView.placeInCenter(of: view)`
     
MIT License


