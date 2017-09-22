# DDCityController
DDCityController
UIImageView *userNameLeftViewIV = [[UIImageView alloc]initWithImage:[UIImage imageNamed:@"ic_camera"]];
            //图片的显示模式
            userNameLeftViewIV.contentMode= UIViewContentModeScaleAspectFill;
            //图片的位置和大小
            userNameLeftViewIV.frame= CGRectMake(0,0,55,20);
            //左视图默认是不显示的 设置为始终显示
            textField.leftViewMode= UITextFieldViewModeAlways;
            textField.leftView= userNameLeftViewIV;
