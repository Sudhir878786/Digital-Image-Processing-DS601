# Question 3

Functions in part 3
1. generate_n_circles :- This function generate random circles with specified dimensions and returns 
                         dimensions of all the non-overlapping circles function gets in 2*n iterations, 
                         if the number of such circles are less than n. Else it returns only n such circles.


2. draw_circles :- This function draws circles on the image with all intensities within circles initialised with 255.


3. fill_image_with_random_intensity_values :- This function fills circles with random intensities within Vf 
                                              and background with random intensities within Vb.


4. draw_border :- It draws the border to the image with specified length.


5. create_image_with_random_circles :- This is the main function that outputs the image with all specified requirements.

                                        It's workflow :- 
                                            It is a recursive function with no base case.

                                            It first calls generate_n_circles, if this function fails to return n non-overlapping circles,
                                            then it gives recursive call to same function with 2*M X 2*N dimensions.

                                            Once we get n non-overlapping circles then the actual execution starts.

                                            We first initialise the image by filling it with 0 intensity everywhere.

                                            Then we call draw_circles function that draws n circles on image with intensity 255.

                                            Then we call fill_image_with_random_intensity_values, which fills image with uniform intensities over the range specified.

                                            Then finally we call draw_border function which draws black coloured border on all 4 sides of the image.



Finally to run this program call create_image_with_random_circles with required inputs.