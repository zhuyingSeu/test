Requirements:

    1.TensorRT5.1.22

Brief Introduction:

    该工程包括主要用到4个接口,SSD检测,卡尔曼跟踪,行人重识别,行人质量评估

    ReID跟踪框架逻辑设计相关文件:MiniTracker.h  MiniTracker.cpp

    SSD检测GPU接口相关文件:DetectorSSD.h

    卡尔曼跟踪接口相关文件:Hungarain.h  Hungarain.cpp  KalmanTracker.cpp Sort.hpp

    行人重识别GPU接口相关文件:ReIDFeatureLib.h

    行人质量评估CPU接口相关文件:Classification.h Classification.cpp

    行人质量评估GPU接口相关文件:PedestrainCleanLib.h



Code Review:

    1.重点看ReID跟踪框架逻辑设计相关文件

    2.ReID跟踪框架逻辑设计的流程图




