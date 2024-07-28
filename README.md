----- JiJi Image Slider -----
To make the JiJi Image Slider work you need to create a JiJiImageArrayDataSet.
<<< Image Slider Setup Sample code >>>

JiJiImageArrayDataSet dataset = new JiJiImageArrayDataSet(
                "src/Resources/1.jpg",
                "src/Resources/2.jpg",
                "src/Resources/3.jpg"
                //Add More
);
jiJiImagesSlider1.setJiJiDataSet(dataset);

<<< Image Slider Setup Sample code >>>
-------------------------------------------------------------------------------
----- JiJi Plaseholder Text Field -----
<<< getText Sample Code >>>

jiJiPlaceholderTextField1.getText();

<<< getText Sample Code >>>
---------------------------------------
<<< Checked Empty Sample Code >>>

jiJiPlaceholderTextField1.isEmpty();

<<< Checked Empty Sample Code >>>
-------------------------------------------------------------------------------
----- JiJi Password Field -----
<<< getPassword Sample Code >>>

jiJiPlaceholderTextField1.getPassword();

<<< getPassword Sample Code >>>
---------------------------------------
<<< Checked Empty Sample Code >>>

jiJiPlaceholderTextField1.emptyPassword;

<<< Checked Empty Sample Code >>>
