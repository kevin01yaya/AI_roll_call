# 他們回來了

https://www.youtube.com/watch?v=KyokbnwdK6A&ab_channel=%E9%9B%BB%E6%A9%9F%E5%B7%A5%E7%A8%8B%E7%B3%BBKevin01yaya

## sorce

    source /opt/intel/openvino/bin/setupvars.sh

## face
```
cd /home/user/AI_roll_call/src
```
```
python ./face_recognition_demo.py -m_fd ~/Desktop/openvino/deployment_tools/tools/model_downloader/intel/face-detection-retail-0004/FP16/face-detection-retail-0004.xml -m_lm ~/Desktop/openvino/deployment_tools/tools/model_downloader/intel/landmarks-regression-retail-0009/FP16/landmarks-regression-retail-0009.xml -m_reid ~/Desktop/openvino/deployment_tools/tools/model_downloader/intel/face-reidentification-retail-0095/FP16/face-reidentification-retail-0095.xml -l /home/user/Desktop/openvino/deployment_tools/inference_engine/lib/intel64/libcpu_extension_sse4.so --verbose -fg "/home/user/AI_roll_call/image/face_cut" --run_detector --allow_grow
```
```
python ./face_recognition_demo.py -m_fd ~/Desktop/openvino/deployment_tools/tools/model_downloader/intel/face-detection-retail-0004/FP16/face-detection-retail-0004.xml -m_lm ~/Desktop/openvino/deployment_tools/tools/model_downloader/intel/landmarks-regression-retail-0009/FP16/landmarks-regression-retail-0009.xml -m_reid ~/Desktop/openvino/deployment_tools/tools/model_downloader/intel/face-reidentification-retail-0095/FP16/face-reidentification-retail-0095.xml -l /home/user/Desktop/openvino/deployment_tools/inference_engine/lib/intel64/libcpu_extension_sse4.so --verbose -fg  "/home/user/AI_roll_call/image/face_gallery"
```
