# LoadingView
A lightweight simpile reusable Loading view in swift

This can be used to show loading activity with spinner. 

This can be used in any view controller or add to any view
 
This class can be extended to custome further loading UI

<img src="https://github.com/Wassmd/LoadingView/blob/master/sample.png" width="375" height= "600">

Below code show how to use in View Controller

        let loadingView = LoadingView()
        view.addSubview(loadingView)
        
        loadingView.translatesAutoresizingMaskIntoConstraints = false
        loadingView.centerXAnchor.constraint(equalTo: view.centerXAnchor).isActive = true
        loadingView.centerYAnchor.constraint(equalTo: view.centerYAnchor).isActive = true
        loadingView.heightAnchor.constraint(equalToConstant: 64).isActive = true
        loadingView.show()
        
When no more need just hide it

     loadingView.hide() 
     
     
     
MIT License


