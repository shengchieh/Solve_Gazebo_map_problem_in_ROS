# Solve_Gazebo_map_problem_in_ROS

wget -r -R "index\.html*" http://models.gazebosim.org/

cp -r ~/models.gazebosim.org ~/.gazebo

cd ~/.gazebo

rm -r models

cp -r models.gazebosim.org models

rm -r models.gazebosim.org
