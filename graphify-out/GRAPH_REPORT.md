# Graph Report - .  (2026-07-20)

## Corpus Check
- 190 files · ~67,610 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 752 nodes · 927 edges · 83 communities (50 shown, 33 thin omitted)
- Extraction: 89% EXTRACTED · 11% INFERRED · 0% AMBIGUOUS · INFERRED: 99 edges (avg confidence: 0.87)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Data IO Storage
- Geometry Utility Functions
- Analysis Engine Pipelines
- 3D Visualization System
- CAS Analysis Descriptors
- Perception Pipeline Concepts
- Camera Descriptor Configuration
- Query Behavior Trees
- Pipeline Descriptor Configuration
- Annotator Package Modules
- Query Action Handling
- CAS View Codecs
- Core Annotator Implementations
- Dynamic Tutorial Modules
- Threaded Pointcloud Annotators
- First Annotator Tutorial
- Pose Geometry Annotations
- Sensor Data Storage
- Feature Comparison System
- General Annotation Types
- WSL Development Setup
- Segmentation Color Annotators
- Semantic Digital Twin
- Image Region Types
- Geometry Conversion Types
- Object Hypothesis Types
- RoboKudo Type Modules
- Annotation Identity Hierarchy
- Query Annotator Protocol
- World Descriptor Visualization
- Camera Component Types
- Position Annotation Types
- RoboKudo Project Background
- Tree Component Modules
- Cylinder Fitting Utilities
- World Descriptor Types
- Global World State
- Docker GPU Runtime
- Annotator Descriptor Parameters
- Cluster Pose Estimation
- Primitive Shape Estimation
- TSDF Object Integration
- Stored Data Engines
- Behavior Tree Rendering
- Annotation Storage Writers
- Camera Viewpoint Visualization
- Object Hypothesis Filtering
- YOLO Object Detection
- Tabletop Localization Subtree
- Task Scheduler Types
- API Reference Generation
- Object Association Annotator
- Object Hypothesis Visualization
- Pipeline Trigger Annotator
- Named Region Definition
- Demo Subtree Engine
- USB Camera Demo
- Looping Behavior Control
- Test Data Utilities
- Blackboard Exception Capture
- Blackboard Exception Clearing
- Image Projection Drawing
- RGBD Pointcloud Generation
- Cuboid Fitting Utility
- Sphere Fitting Utility
- Shape Model Selection
- Dynamic Subtree Repair
- World Entity Tracker
- Query Answer Generation
- Camera Transform Utility
- Pointcloud Transform Utility
- Image Mask Adjustment
- Bounding Rectangle Clamping
- Image Cropping Utility
- Rectangle Drawing Utility
- BGR HSV Conversion
- RGB HSV Conversion
- Coordinate Scaling Utility
- Image Boundary Check
- Bounding Rectangle Validation
- Timing Decorator Utility
- Blackboard Exception Lookup
- File Loading Utility

## God Nodes (most connected - your core abstractions)
1. `BaseAnnotator` - 33 edges
2. `Annotation` - 24 edges
3. `robokudo.annotators` - 21 edges
4. `AnalysisEngineInterface` - 19 edges
5. `Camera Configuration Module` - 16 edges
6. `robokudo.io.cas_view_codecs` - 14 edges
7. `RoboKudo Utilities` - 14 edges
8. `robokudo.io` - 13 edges
9. `FeatureComparator` - 13 edges
10. `ViewCodec` - 12 edges

## Surprising Connections (you probably didn't know these)
- `Demo Perception Pipeline` --semantically_similar_to--> `Tabletop Segmentation Pipeline`  [INFERRED] [semantically similar]
  tutorials/run_pipeline.md.txt → autoapi/robokudo/descriptors/analysis_engines/realsense/index.rst.txt
- `Query Pipeline` --semantically_similar_to--> `Pipeline`  [INFERRED] [semantically similar]
  tutorials/Advanced_query_handling.md.txt → autoapi/robokudo/gui/index.rst.txt
- `MongoDB Sensor Data Workflow for Faster Development` --semantically_similar_to--> `Filesystem Sensor Data Storage`  [INFERRED] [semantically similar]
  tutorials/database_storage.md.txt → autoapi/robokudo/annotators/file_writer/index.rst.txt
- `Query-response Pipeline` --semantically_similar_to--> `Query Interface`  [INFERRED] [semantically similar]
  autoapi/robokudo/descriptors/analysis_engines/query/index.rst.txt → tutorials/query_interface.md.txt
- `Demo Perception Pipeline` --semantically_similar_to--> `RoboKudo Pipeline`  [INFERRED] [semantically similar]
  tutorials/run_pipeline.md.txt → introduction.md.txt

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Object Hypothesis Perception Pipeline** — autoapi_robokudo_annotators_image_cluster_extractor_index_rst_imageclusterextractor, autoapi_robokudo_annotators_byte_track_annotator_index_rst_bytetrackannotator, autoapi_robokudo_annotators_cluster_color_index_rst_clustercolorannotator, autoapi_robokudo_annotators_cluster_color_histogram_index_rst_clustercolorhistogramannotator, autoapi_robokudo_annotators_cluster_pose_bb_index_rst_clusterposebbannotator, autoapi_robokudo_annotators_cluster_pose_pca_index_rst_clusterposepcaannotator, autoapi_robokudo_annotators_cluster_position_index_rst_clusterpositionannotator, autoapi_robokudo_annotators_icp_pose_refinement_index_rst_icpposerefinementannotator, autoapi_robokudo_annotators_cas_check_index_rst_cascheckohexists [INFERRED 0.85]
- **Semantic World and Region Integration** — autoapi_robokudo_annotators_location_index_rst_locationannotator, autoapi_robokudo_annotators_region_filter_index_rst_regionfilter, autoapi_robokudo_annotators_semantic_world_connector_index_rst_semanticdigitaltwinconnector, autoapi_robokudo_annotators_static_object_detector_index_rst_staticobjectdetectorannotator, autoapi_robokudo_world_descriptor_index_rst_baseworlddescriptor [INFERRED 0.85]
- **Object Hypothesis Refinement Pipeline** — autoapi_robokudo_annotators_object_hypothesis_visualizer_index_rst_objecthypothesisvisualizer, autoapi_robokudo_annotators_outlier_removal_objecthypothesis_index_rst_outlierremovalonobjecthypothesisannotator, autoapi_robokudo_annotators_pointcloud_cluster_extractor_index_rst_pointcloudclusterextractor, autoapi_robokudo_annotators_pointcloud_cluster_extractor_index_rst_naivepointcloudclusterextractor, autoapi_robokudo_annotators_shape_estimator_index_rst_shapeestimatorannotator, autoapi_robokudo_annotators_simple_yolo_annotator_index_rst_simpleyoloannotator [INFERRED 0.75]
- **Docker GPU Visualization Runtime** — tutorials_docker_rk_md_robokudo_docker_image, tutorials_docker_rk_md_nvidia_container_toolkit, tutorials_docker_rk_md_nvidia_gpu_runtime, tutorials_docker_rk_md_x11_graphics_support [EXTRACTED 1.00]
- **Tabletop Segmentation Pipeline Family** — autoapi_robokudo_descriptors_analysis_engines_demo_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_demo_from_storage_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_filereader_index_rst_analysisengine [INFERRED 0.95]
- **Stored Data Reuse Workflows** — autoapi_robokudo_descriptors_analysis_engines_annotations_from_storage_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_demo_from_storage_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_filewriter_from_storage_index_rst_analysisengine [INFERRED 0.85]
- **Query Processing Three-part Flow** — tutorials_query_interface_md_query_retrieval, tutorials_query_interface_md_query_interpretation, tutorials_query_interface_md_query_answer_generation [EXTRACTED 1.00]
- **Stored Camera Data Perception Engines** — autoapi_robokudo_descriptors_analysis_engines_query_demo_from_storage_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_query_startstop_pipeline_from_storage_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_regionfilter_from_storage_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_static_detector_from_storage_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_tiago_demo_from_storage_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_world_descriptor_from_storage_index_rst_analysisengine [INFERRED 0.85]
- **Tabletop Object Perception Implementations** — autoapi_robokudo_descriptors_analysis_engines_realsense_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_query_demo_from_storage_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_semdt_demo_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_semdt_demo_from_storage_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_semdt_demo_from_storage_full_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_tiago_demo_index_rst_analysisengine, autoapi_robokudo_descriptors_analysis_engines_subtree_tabletop_object_localization_index_rst_subtree, tutorials_run_pipeline_md_demo_pipeline [INFERRED 0.85]
- **Composable Camera Configuration Components** — autoapi_robokudo_descriptors_camera_configs_components_index_rst_depthcomponent, autoapi_robokudo_descriptors_camera_configs_components_index_rst_colorcomponent, autoapi_robokudo_descriptors_camera_configs_components_index_rst_tfcomponent, autoapi_robokudo_descriptors_camera_configs_components_index_rst_stableviewpointcomponent, autoapi_robokudo_descriptors_camera_configs_components_index_rst_worlddescriptorcomponent, autoapi_robokudo_descriptors_camera_configs_components_index_rst_rgbdcomponent [EXTRACTED 1.00]
- **Camera Configuration Registry Ecosystem** — autoapi_robokudo_descriptors_camera_configs_index_rst_camera_configuration_module, autoapi_robokudo_descriptors_camera_configs_registry_index_rst_cameraconfigregistry, autoapi_robokudo_descriptors_camera_configs_config_kinect_robot_index_rst_kinectcameraconfig, autoapi_robokudo_descriptors_camera_configs_config_hsr_index_rst_hsrcameraconfig, autoapi_robokudo_descriptors_camera_configs_config_realsense_index_rst_realsensecameraconfig, autoapi_robokudo_descriptors_camera_configs_config_filereader_playback_index_rst_filereadercameraconfig, autoapi_robokudo_descriptors_camera_configs_config_mongodb_playback_index_rst_mongocameraconfig [EXTRACTED 1.00]
- **Advanced Query Behavior Tree Pipeline** — tutorials_advanced_query_handling_md_query_pipeline, tutorials_advanced_query_handling_md_pipeline_init, tutorials_advanced_query_handling_md_queryannotator, tutorials_advanced_query_handling_md_conditionalselector, tutorials_advanced_query_handling_md_tasksequence, tutorials_advanced_query_handling_md_queryfeedbackandcount, tutorials_advanced_query_handling_md_generatequeryresult [EXTRACTED 1.00]
- **WSL RoboKudo Development Stack** — tutorials_wsl_installation_md_wsl2, tutorials_wsl_installation_md_ubuntu_20_04_wsl, tutorials_wsl_installation_md_vcxsrv_display_configuration, tutorials_wsl_installation_md_ros_noetic, tutorials_wsl_installation_md_robokudo_catkin_workspace, tutorials_wsl_installation_md_opencv_python, tutorials_wsl_installation_md_pycharm_wsl_host, tutorials_wsl_installation_md_rk_venv [EXTRACTED 1.00]
- **CAS View Codec Family** — autoapi_robokudo_io_cas_view_codecs_index_rst_viewcodec, autoapi_robokudo_io_cas_view_codecs_index_rst_jsonlikecodec, autoapi_robokudo_io_cas_view_codecs_index_rst_tuplecodec, autoapi_robokudo_io_cas_view_codecs_index_rst_bytescodec, autoapi_robokudo_io_cas_view_codecs_index_rst_numpycodec, autoapi_robokudo_io_cas_view_codecs_index_rst_rosmessagecodec, autoapi_robokudo_io_cas_view_codecs_index_rst_open3dpointcloudcodec, autoapi_robokudo_io_cas_view_codecs_index_rst_open3dpinholecameraintrinsiccodec, autoapi_robokudo_io_cas_view_codecs_index_rst_stampedtransformcodec, autoapi_robokudo_io_cas_view_codecs_index_rst_homogeneoustransformationmatrixcodec, autoapi_robokudo_io_cas_view_codecs_index_rst_krroodcodec [EXTRACTED 1.00]
- **Semantic Twin Object Diff Lifecycle** — autoapi_robokudo_io_semantic_digital_twin_index_rst_worlddiff, autoapi_robokudo_io_semantic_digital_twin_index_rst_addobjectdiff, autoapi_robokudo_io_semantic_digital_twin_index_rst_updateobjectdiff, autoapi_robokudo_io_semantic_digital_twin_index_rst_removeobjectdiff [INFERRED 0.95]
- **Configured Analysis Engine Pipeline** — tutorials_configure_your_annotator_md_analysisengine, autoapi_robokudo_pipeline_index_rst_pipeline, autoapi_robokudo_idioms_index_rst_pipeline_init, tutorials_configure_your_annotator_md_pointcloudcropannotator, tutorials_configure_your_annotator_md_myfirstannotator [EXTRACTED 1.00]
- **Robokudo Type Hierarchy** — autoapi_robokudo_types_core_index_rst_type, autoapi_robokudo_types_core_index_rst_annotation, autoapi_robokudo_types_core_index_rst_identifiableannotation, autoapi_robokudo_types_scene_index_rst_analyzableannotation, autoapi_robokudo_types_scene_index_rst_objecthypothesis, autoapi_robokudo_types_scene_index_rst_humanhypothesis [EXTRACTED 1.00]
- **Annotation to Object Designator Conversion** — autoapi_robokudo_utils_annotation_conversion_index_rst_annotation2odconverter, autoapi_robokudo_utils_annotation_conversion_index_rst_semanticcolor2odconverter, autoapi_robokudo_utils_annotation_conversion_index_rst_classification2odconverter, autoapi_robokudo_utils_annotation_conversion_index_rst_stampedpose2odconverter, autoapi_robokudo_utils_annotation_conversion_index_rst_pose2odconverter, autoapi_robokudo_utils_annotation_conversion_index_rst_position2odconverter, autoapi_robokudo_utils_annotation_conversion_index_rst_stampedposition2odconverter, autoapi_robokudo_utils_annotation_conversion_index_rst_boundingbox3dforshapesizeconverter, autoapi_robokudo_utils_annotation_conversion_index_rst_shape2odconverter, autoapi_robokudo_utils_annotation_conversion_index_rst_cuboid2odconverter, autoapi_robokudo_utils_annotation_conversion_index_rst_cylinder2odconverter, autoapi_robokudo_utils_annotation_conversion_index_rst_sphere2odconverter, autoapi_robokudo_utils_annotation_conversion_index_rst_location2odconverter [EXTRACTED 1.00]
- **Feature Similarity Framework** — autoapi_robokudo_utils_comparator_factories_index_rst_featurecomparatorfactory, autoapi_robokudo_utils_comparators_index_rst_featurecomparator, autoapi_robokudo_utils_comparators_index_rst_translationcomparator, autoapi_robokudo_utils_comparators_index_rst_orientationcomparator, autoapi_robokudo_utils_comparators_index_rst_bboxcomparator, autoapi_robokudo_utils_comparators_index_rst_sizecomparator, autoapi_robokudo_utils_comparators_index_rst_histogramcomparator, autoapi_robokudo_utils_comparators_index_rst_semanticcolorcomparator, autoapi_robokudo_utils_comparators_index_rst_classificationcomparator, autoapi_robokudo_utils_comparators_index_rst_additionaldatacomparator, autoapi_robokudo_utils_comparators_index_rst_roicomparator, autoapi_robokudo_utils_comparators_index_rst_maskcomparator, autoapi_robokudo_utils_comparators_index_rst_imageroicomparator, autoapi_robokudo_utils_comparators_index_rst_posecomparator [EXTRACTED 1.00]
- **Primitive Shape Fitting Pipeline** — autoapi_robokudo_utils_shape_fitting_index_rst_fit_sphere, autoapi_robokudo_utils_shape_fitting_index_rst_fit_cylinder, autoapi_robokudo_utils_shape_fitting_index_rst_fit_cuboid, autoapi_robokudo_utils_shape_fitting_index_rst_select_best_shape [EXTRACTED 1.00]
- **Shared-Memory Geometry Serialization** — autoapi_robokudo_vis_multiprocessed_o3d_visualizer_index_rst_pointcloudmemorymap, autoapi_robokudo_vis_multiprocessed_o3d_visualizer_index_rst_linesetmemorymap, autoapi_robokudo_vis_multiprocessed_o3d_visualizer_index_rst_trianglemeshmemorymap, autoapi_robokudo_vis_multiprocessed_o3d_visualizer_index_rst_orientedboundingboxmemorymap, autoapi_robokudo_vis_multiprocessed_o3d_visualizer_index_rst_voxelgrid3dmemorymap, autoapi_robokudo_vis_multiprocessed_o3d_visualizer_index_rst_octree3dmemorymap [EXTRACTED 1.00]
- **RoboKudo Visualization Backends** — autoapi_robokudo_vis_cv_visualizer_index_rst_cvvisualizer, autoapi_robokudo_vis_o3d_visualizer_index_rst_o3dvisualizer, autoapi_robokudo_vis_multiprocessed_o3d_visualizer_index_rst_o3dvisualizer, autoapi_robokudo_vis_ros_visualizer_index_rst_sharedrosvisualizer, autoapi_robokudo_vis_ros_visualizer_index_rst_allannotatorrosvisualizer, autoapi_robokudo_vis_visualizer_manager_index_rst_visualizationmanager [INFERRED 0.85]

## Communities (83 total, 33 thin omitted)

### Community 0 - "Data IO Storage"
Cohesion: 0.06
Nodes (50): BBIdentifier, robokudo.identifier, non_query_pipeline_init, pipeline_init, robokudo.idioms, robokudo, CameraInterface, depth_convert_workaround (+42 more)

### Community 1 - "Geometry Utility Functions"
Cohesion: 0.05
Nodes (47): Hypothesis Comparators, HypothesisComparator, ObjectHypothesisComparator, Weighted Hypothesis Similarity, RoboKudo Utilities, configure_logging, DynamicCompactFormatter, Logging Configuration (+39 more)

### Community 2 - "Analysis Engine Pipelines"
Cohesion: 0.06
Nodes (43): Query Complex AnalysisEngine, AnalysisEngineInterface, Query Response Pipeline, Stored-Data Query AnalysisEngine, MongoDB Stored Camera Data, Stored-Data Query Pipeline, Start/Stop Pipeline AnalysisEngine, Continuous Perception Start/Stop Control (+35 more)

### Community 3 - "3D Visualization System"
Cohesion: 0.06
Nodes (38): trimesh_to_o3d_mesh, ROS-OpenCV Image Conversion, CVVisualizer, OpenCV Visualization, RoboKudo Visualization, ArrayMemoryMap, Geometry3DMemoryMap, Geometry3DMemoryMapFactory (+30 more)

### Community 4 - "CAS Analysis Descriptors"
Cohesion: 0.05
Nodes (37): Analysis Scopes, EmptyAnnotator, FailingAnnotator, FakeCollectionReaderAnnotator, robokudo.annotators.testing, ScopedAnnotator, SlowAnnotator, Redraw (+29 more)

### Community 5 - "Perception Pipeline Concepts"
Cohesion: 0.08
Nodes (35): Numbers Query AnalysisEngine, BaseAnnotator, CheckQueryType, Numbers Query Behavior Tree, PrintNumbers, Annotation, Annotator, Behavior Trees (+27 more)

### Community 6 - "Camera Descriptor Configuration"
Cohesion: 0.12
Nodes (28): OpenCVCameraConfig, FileReaderCameraConfig, HsrHandCameraConfig, HsrCameraConfig, HsrRos2CameraConfig, KinectCameraConfig, KinectWoTfCameraConfig, MongoCameraConfig (+20 more)

### Community 7 - "Query Behavior Trees"
Cohesion: 0.10
Nodes (26): Behavior Tree Visualization, generate_pydot_graph, render_dot_tree, stringify_dot_tree, write_timing_info_to_csv, grow_tree, Pipeline, SetPipelineRedraw (+18 more)

### Community 8 - "Pipeline Descriptor Configuration"
Cohesion: 0.13
Nodes (24): Annotator visualization, Common Analysis Structure, Pipeline, py_trees Sequence, robokudo.pipeline, main, robokudo.scripts.main, run_ae (+16 more)

### Community 9 - "Annotator Package Modules"
Cohesion: 0.09
Nodes (23): robokudo.annotators, LambdaFunctionAnnotator, robokudo.annotators.lambda_function, ObjectPoseVisualizer, robokudo.annotators.object_pose_visualizer, PointcloudCheckAnnotator, robokudo.annotators.pointcloud_check, PointcloudCropAnnotator (+15 more)

### Community 10 - "Query Action Handling"
Cohesion: 0.12
Nodes (21): AbortGoal, Action Server Lifecycle Control, ActionServerActive, ActionServerCheck, ActionServerNoPreemptRequest, ActionServerPresentAndDone, robokudo.behaviours.action_server_checks, RunningUntilExceptionHandled (+13 more)

### Community 11 - "CAS View Codecs"
Cohesion: 0.18
Nodes (19): Open3DPointCloudJSONSerializer, BytesCodec, CASViewCodecRegistry, HomogeneousTransformationMatrixCodec, JsonLikeCodec, KrroodCodec, NumpyCodec, Open3DPinholeCameraIntrinsicCodec (+11 more)

### Community 12 - "Core Annotator Implementations"
Cohesion: 0.13
Nodes (18): BlurAnnotator, Laplacian Variance Blur Metric, ByteTrack Object Tracking, ByteTrackAnnotator, CLIP Vocabulary Similarity Classification, ClipAnnotator, ClusterPositionAnnotator, Point Cloud Centroid Position Estimation (+10 more)

### Community 13 - "Dynamic Tutorial Modules"
Cohesion: 0.12
Nodes (18): Dynamic Module Loading, ModuleLoader.load_ae, ModuleLoader.load_world_descriptor, ModuleLoader, RobokudoModuleType, load_world_descriptor, World Descriptor Utilities, Custom Analysis Engines (+10 more)

### Community 14 - "Threaded Pointcloud Annotators"
Cohesion: 0.13
Nodes (17): ThreadedAnnotator, Worker, ICPPoseRefinementAnnotator, Iterative Closest Point Pose Refinement, PLY Reference Point Cloud Models, LocationAnnotator, robokudo.annotators.location, PlaneAnnotator (+9 more)

### Community 15 - "First Annotator Tutorial"
Cohesion: 0.12
Nodes (17): generate_source_name, get_cam_to_world_transform_matrix, get_color_image, resize_mask, scale_cam_intrinsics, transform_cloud_from_cam_to_world, get_scaled_color_image_for_depth_image, publish_variables (+9 more)

### Community 16 - "Pose Geometry Annotations"
Cohesion: 0.15
Nodes (15): BoundingBox3DAnnotation, PoseAnnotation, StampedPoseAnnotation, StampedTransformAnnotation, BoundingBox3D, Pose, StampedPose, StampedTransform (+7 more)

### Community 17 - "Sensor Data Storage"
Cohesion: 0.16
Nodes (14): AnalysisEngineInterface, Behavior Tree Analysis Engine, SubtreeInterface, CollectionReaderAnnotator, Sensor Data Collection and CAS Initialization, Filesystem Sensor Data Storage, FileWriter, ImagePreprocessorAnnotator (+6 more)

### Community 18 - "Feature Comparison System"
Cohesion: 0.18
Nodes (14): ColorHistogram, SemanticColor, SemanticColor2ODConverter, FeatureComparatorFactory, AdditionalDataComparator, FeatureComparator, HistogramComparator, ImageROIComparator (+6 more)

### Community 19 - "General Annotation Types"
Cohesion: 0.15
Nodes (13): Encoding, LocationAnnotation, Plane, SpatiallyNearestAnnotation, TextAnnotation, Annotation, TSDFAnnotation, ActivityAnnotation (+5 more)

### Community 20 - "WSL Development Setup"
Cohesion: 0.18
Nodes (13): opencv-python, PyCharm Professional Edition, PyCharm WSL Host, rk_venv, robokudo_ws Catkin Workspace, Official RoboKudo Installation Guide, RoboKudo Repository, ROS Noetic (+5 more)

### Community 21 - "Segmentation Color Annotators"
Cohesion: 0.17
Nodes (12): any_of_type_present, CASCheckAnnotationTypeExists, CASCheckFunc, CASCheckOHExists, ClusterColorHistogramAnnotator, Hue-Saturation Histogram Analysis, ClusterColorAnnotator, Color (+4 more)

### Community 22 - "Semantic Digital Twin"
Cohesion: 0.30
Nodes (12): AddCollisionCommand, AddObjectDiff, Object, RemoveCollisionCommand, RemoveObjectDiff, robokudo.io.semantic_digital_twin, SemanticDigitalTwinAdapter, TrackedObject (+4 more)

### Community 23 - "Image Region Types"
Cohesion: 0.24
Nodes (12): Query, Type, ImageROI, Point2D, Rect, CameraInfo, Header, RegionOfInterest (+4 more)

### Community 24 - "Geometry Conversion Types"
Cohesion: 0.25
Nodes (11): Cuboid, Cylinder, Shape, Sphere, Annotation2ODConverter, Cuboid2ODConverter, Cylinder2ODConverter, Pose2ODConverter (+3 more)

### Community 25 - "Object Hypothesis Types"
Cohesion: 0.22
Nodes (9): Classification, CloudAnnotation, Points3D, FaceAnnotation, HumanHypothesis, ObjectHypothesis, Classification2ODConverter, draw_bounding_boxes_from_object_hypotheses (+1 more)

### Community 26 - "RoboKudo Type Modules"
Cohesion: 0.25
Nodes (8): robokudo.types.annotation, robokudo.types.core, robokudo.types.cv, robokudo.types.human, robokudo.types, robokudo.types.ros, robokudo.types.scene, robokudo.types.tf

### Community 27 - "Annotation Identity Hierarchy"
Cohesion: 0.29
Nodes (8): Identifiable, IdentifiableAnnotation, Nameable, AnalyzableAnnotation, ParthoodComponentHypothesis, ParthoodFeatureHypothesis, ParthoodHypothesis, RegionHypothesis

### Community 28 - "Query Annotator Protocol"
Cohesion: 0.29
Nodes (7): GenerateQueryResult, QueryActionServer, QueryAnnotator, QueryFeedback, QueryFeedbackAndCount, QueryReply, robokudo.annotators.query

### Community 29 - "World Descriptor Visualization"
Cohesion: 0.29
Nodes (7): robokudo.annotators.world_descriptor_bootstrap, Shared World Augmentation, WorldDescriptorBootstrapAnnotator, WorldDescriptorBootstrapError, robokudo.annotators.world_visualizer, Shared World Visualization, WorldVisualizer

### Community 30 - "Camera Component Types"
Cohesion: 0.33
Nodes (6): BaseCameraConfig, ColorComponent, DepthComponent, RGBDComponent, StableViewpointComponent, TfComponent

### Community 31 - "Position Annotation Types"
Cohesion: 0.33
Nodes (6): PositionAnnotation, StampedPositionAnnotation, Position, StampedPosition, Position2ODConverter, StampedPosition2ODConverter

### Community 32 - "RoboKudo Project Background"
Cohesion: 0.50
Nodes (5): About the RoboKudo Framework, DFG-funded CRC 1320 EASE, Institute for Artificial Intelligence, Prof. Michael Beetz, University of Bremen

### Community 33 - "Tree Component Modules"
Cohesion: 0.40
Nodes (5): robokudo.tree_components, robokudo.tree_components.looping, robokudo.tree_components.query_based_task_scheduler, robokudo.tree_components.render_dot, robokudo.tree_components.task_scheduler

### Community 34 - "Cylinder Fitting Utilities"
Cohesion: 0.40
Nodes (5): CylinderFit, CylinderFitConstraints, CylinderInitializationSettings, fit_cylinder, Multi-Start Cylinder Fitting

### Community 35 - "World Descriptor Types"
Cohesion: 0.40
Nodes (5): BaseWorldDescriptor, ObjectSpec, PredefinedObject, RegionSpec, robokudo.world_descriptor

### Community 36 - "Global World State"
Cohesion: 0.40
Nodes (5): clear_world, set_world, unsafe_clear_world, unsafe_set_world, world_instance

### Community 37 - "Docker GPU Runtime"
Cohesion: 0.40
Nodes (5): NVIDIA Container Toolkit, NVIDIA GPU Runtime, RoboKudo Docker Image, Running RoboKudo in a Docker Container, X11 Graphics Support

### Community 38 - "Annotator Descriptor Parameters"
Cohesion: 0.50
Nodes (4): AnnotatorPredefinedParameters, BaseAnnotator.Descriptor, BaseAnnotator.Descriptor.Capabilities, BaseAnnotator.Descriptor.Parameters

### Community 39 - "Cluster Pose Estimation"
Cohesion: 0.50
Nodes (4): ClusterPoseBBAnnotator, Oriented Bounding Box Pose Estimation, ClusterPosePCAAnnotator, PCA Pose Estimation

### Community 40 - "Primitive Shape Estimation"
Cohesion: 0.50
Nodes (4): CylinderAxisCandidate, Primitive Shape Fitting, robokudo.annotators.shape_estimator, ShapeEstimatorAnnotator

### Community 41 - "TSDF Object Integration"
Cohesion: 0.67
Nodes (4): Per-object TSDF Integration, robokudo.annotators.tsdf_annotator, TSDFAnnotator, TSDFAnnotatorVisualizationModes

### Community 42 - "Stored Data Engines"
Cohesion: 0.50
Nodes (4): Annotations From Storage AnalysisEngine, robokudo.descriptors.analysis_engines.annotations_from_storage, File Writer From Storage AnalysisEngine, robokudo.descriptors.analysis_engines.filewriter_from_storage

### Community 43 - "Behavior Tree Rendering"
Cohesion: 0.50
Nodes (4): create_dir_if_not_exists, render_now, RenderTreeToDot, RenderTreeToDotDecorator

### Community 44 - "Annotation Storage Writers"
Cohesion: 1.00
Nodes (3): AnnotationPublisherWriter, AnnotationStorageWriter, CAS Annotation JSON Serialization

### Community 45 - "Camera Viewpoint Visualization"
Cohesion: 0.67
Nodes (3): Camera Viewpoint and Reference Frame Visualization, CameraViewpointVisualizer, setup_world_for_camera_frame

### Community 46 - "Object Hypothesis Filtering"
Cohesion: 0.67
Nodes (3): OutlierRemovalOnObjectHypothesisAnnotator, _PYTYPE_TO_ROS_FIELD, robokudo.annotators.outlier_removal_objecthypothesis

### Community 47 - "YOLO Object Detection"
Cohesion: 0.67
Nodes (3): robokudo.annotators.simple_yolo_annotator, SimpleYoloAnnotator, YOLO Object Detection

### Community 48 - "Tabletop Localization Subtree"
Cohesion: 0.67
Nodes (3): Tabletop Object Localization Subtree, SubtreeInterface, Tabletop Object Localization Sequence

### Community 49 - "Task Scheduler Types"
Cohesion: 1.00
Nodes (3): QueryBasedScheduler, IterativeTaskScheduler, TaskSchedulerBase

## Ambiguous Edges - Review These
- `any_of_type_present` → `CASCheckAnnotationTypeExists`  [AMBIGUOUS]
  autoapi/robokudo/annotators/cas_check/index.rst.txt · relation: references
- `OrbbecCameraConfig` → `OrbbecCameraConfig Without Transform Lookup`  [AMBIGUOUS]
  autoapi/robokudo/descriptors/camera_configs/config_orbbec_wo_transform/index.rst.txt · relation: implements

## Knowledge Gaps
- **270 isolated node(s):** `DFG-funded CRC 1320 EASE`, `University of Bremen`, `RoboKudo API Reference`, `Sphinx AutoAPI`, `Behavior Tree Analysis Engine` (+265 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **33 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `any_of_type_present` and `CASCheckAnnotationTypeExists`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `OrbbecCameraConfig` and `OrbbecCameraConfig Without Transform Lookup`?**
  _Edge tagged AMBIGUOUS (relation: implements) - confidence is low._
- **Why does `BaseAnnotator` connect `Core Annotator Implementations` to `Annotator Descriptor Parameters`, `Cluster Pose Estimation`, `Annotator Package Modules`, `Annotation Storage Writers`, `Camera Viewpoint Visualization`, `Threaded Pointcloud Annotators`, `Object Hypothesis Filtering`, `Sensor Data Storage`, `Object Association Annotator`, `Object Hypothesis Visualization`, `Segmentation Color Annotators`, `Pipeline Trigger Annotator`?**
  _High betweenness centrality (0.018) - this node is a cross-community bridge._
- **Why does `RoboKudo Utilities` connect `Geometry Utility Functions` to `Dynamic Tutorial Modules`?**
  _High betweenness centrality (0.014) - this node is a cross-community bridge._
- **Why does `robokudo.io` connect `Data IO Storage` to `CAS View Codecs`, `Semantic Digital Twin`?**
  _High betweenness centrality (0.012) - this node is a cross-community bridge._
- **What connects `DFG-funded CRC 1320 EASE`, `University of Bremen`, `RoboKudo API Reference` to the rest of the system?**
  _270 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Data IO Storage` be split into smaller, more focused modules?**
  _Cohesion score 0.06285714285714286 - nodes in this community are weakly interconnected._