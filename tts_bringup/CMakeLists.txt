cmake_minimum_required(VERSION 3.5)
project(tts_bringup)

# 依存関係を見つける
find_package(ament_cmake REQUIRED)
find_package(audio_common REQUIRED)
find_package(tts_ros REQUIRED)

# ヘッダーファイルの追加の場所を指定
include_directories(include)

# 実行可能ファイルを追加し、ライブラリをリンク
#add_executable(tts_bringup_node src/tts_bringup_node.cpp)
#ament_target_dependencies(tts_bringup_node audio_common tts_ros)




ament_package()
