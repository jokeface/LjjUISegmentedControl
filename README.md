# LjjUISegmentedControl
This is my first time that write something at this website,Thanks;
This code is for the man who wants to find the UISegmentedControl witch has Underlines and Animations;
No more to say，let's begin;
# First create
    LjjUISegmentedControl* ljjuisement=[[LjjUISegmentedControl alloc]initWithFrame:CGRectMake(0, 0, [UIScreen mainScreen].bounds.size.width, self.view.frame.size.height)];
    NSArray* ljjarray=[NSArray arrayWithObjects:@"未领餐",@"待付款",@"已领餐",@"退款",nil];
    [ljjuisement AddSegumentArray:ljjarray];
    About ljjarray:You can add any object whose type is "NSString",it is like the segmentTitle of UISegmentedControl;
# Change the background color
    ljjuisement.LJBackGroundColor=[UIColor BlackColor];
# Change Title color
    ljjuisement.titleColor=[UIColor BlackColor];
# Change the Color of selectionButton
    ljjuisement.selectColor=[UIColor BlackColor];
# Change the buttonTitle Font
    ljjuisement.titleFont=[UIFont fontWithName:@".Helvetica Neue Interface" size:14.0f];
# Select the Button
    [ljjuisement selectTheSegument:1];
# protocol
-(void)uisegumentSelectionChange:(NSInteger)selection;
# end
Thats All,Thanks
