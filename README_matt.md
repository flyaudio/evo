# matt 

入口
entry_points.py

main_traj.py
    trajetory.py
        align_trajectory
        打印其中的r_a,t_a,s  就是对齐后的T 和s
        然后需要做的是将2D的(x,y,theta),转换成3D的(x,y,z,quaternion)
main_rpe.py




    trajetory.py
class Trajectory(PoseTrajectory3D):
           class PoseTrajectory3D(PosePath3D, object):
                            class PosePath3D(object):
