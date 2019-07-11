# SnackBarHelperClass
This is just a helper to prevent you from boiler plate coding in Java android 

OPTIONS:
1) Change the color of text and Action Text
2) Add auto hide time and hide every where you want 
3) Change the background color 
4) suitable for Fragment and Acitivty
5) Add font to text action bar and textvew
6) forceRtl for non-English and Right to left languages 


With Warm Thanks:
https://github.com/google-ar/sceneform-android-sdk/blob/master/samples/augmentedimage/app/src/main/java/com/google/ar/sceneform/samples/common/helpers/SnackbarHelper.java 


HOW TO USE:

SnackbarHelper.newInstance(getActivity()) //this is for Fragmnets, you can pass AppCompatActivity too
        .setIcon(R.drawable.ic_error, SnackbarHelper.DIRECTION.RIGHT) // what icon to show and direction of inflating it 
        .forceRtl() //for rtl for non-english lang
        .setFont(PATH TO ASSETS FOLDER) //you can set font from asset folder 
        .setActionBarBackgorundColor(COLOR)
        .setAutoHideTime(DELAY TO DISMISS)
        .showError(TEXT TO SHOW HERE);
        
        
IF YOU ADD NEW AMAZING FEATURES AND CHANGE THE CODE STYLE IN A BETTER FORM PLEASE COMMIT 

Thank you


