# LoadingView
A lightweight simpile reusable Loading view in swift

This can be used to show loading activity with spinner. 

This can be used in any view controller or add to any view
 
The class can be extended to custome view

![](https://github.com/Wassmd/LoadingView/blob/master/sample.png =250x250)

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


