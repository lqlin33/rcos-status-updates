## Last Week's Accomplishments

This past week I figured out what was causing the errors in my unit tests. Certain models took a field as their primary key, and I wasn't specifying that field so many-to-many relationships couldn't be used. I also learned the importance of saving objects in Django and when it is necessary to do so. As I finished writing the unit tests, I also realized some fixes that could be applied to the petitions model itself and created an issue for that. I also talked with my mentor about whether or not to keep setter and getter functions in the model, and we both decided that while they aren't necessary, we would leave the functions in for now.

## This Week's Plan

This week I plan to finish up writing the unit tests (only about one more to go!) Afterwards I would like to start working on the fixes in the petitions model that I noticed and start looking into admin functionalities.

## Anything Blocking?

None that I know.