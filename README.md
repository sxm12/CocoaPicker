##CocoaPicker --仿QQ图片选择器


###如何使用

 ```objective-c
self.view.window.rootViewController.modalPresentationStyle = UIModalPresentationCurrentContext;//半透明
        CocoaPickerViewController *transparentView = [[CocoaPickerViewController alloc] init];
        transparentView.delegate = self;
        transparentView.modalPresentationStyle = UIModalPresentationOverFullScreen;
        transparentView.modalTransitionStyle = UIModalTransitionStyleCrossDissolve;
        transparentView.view.frame=self.view.frame;
        transparentView.view.backgroundColor=[[UIColor blackColor] colorWithAlphaComponent:.5];
        transparentView.view.superview.backgroundColor = [UIColor clearColor];
        [self presentViewController:transparentView animated:YES completion:nil];Log(@"Error: %@", error);
}];
```
      


###截图0


![Image](image/CocoaPicker1.jpg) 

###截图1

![Image](image/CocoaPicker0.jpg) 



