cmake_minimum_required(VERSION 3.9)
set (CMAKE_CXX_STANDARD 17)

project(joltc)
include_directories(.)

add_library(joltc STATIC
    JoltC/JoltPhysicsC.cpp


    Jolt/AABBTree/AABBTreeBuilder.cpp
    Jolt/Core/Color.cpp
    Jolt/Core/Factory.cpp
    Jolt/Core/IssueReporting.cpp
    Jolt/Core/JobSystemThreadPool.cpp
    Jolt/Core/JobSystemWithBarrier.cpp
    Jolt/Core/LinearCurve.cpp
    Jolt/Core/Memory.cpp
    Jolt/Core/Profiler.cpp
    Jolt/Core/RTTI.cpp
    Jolt/Core/Semaphore.cpp
    Jolt/Core/StringTools.cpp
    Jolt/Core/TickCounter.cpp
    Jolt/Geometry/ConvexHullBuilder2D.cpp
    Jolt/Geometry/ConvexHullBuilder.cpp
    Jolt/Geometry/Indexify.cpp
    Jolt/Geometry/OrientedBox.cpp
    Jolt/Math/UVec4.cpp
    Jolt/Math/Vec3.cpp
    Jolt/ObjectStream/ObjectStreamBinaryIn.cpp
    Jolt/ObjectStream/ObjectStreamBinaryOut.cpp
    Jolt/ObjectStream/ObjectStream.cpp
    Jolt/ObjectStream/ObjectStreamIn.cpp
    Jolt/ObjectStream/ObjectStreamOut.cpp
    Jolt/ObjectStream/ObjectStreamTextIn.cpp
    Jolt/ObjectStream/ObjectStreamTextOut.cpp
    Jolt/ObjectStream/SerializableObject.cpp
    Jolt/ObjectStream/TypeDeclarations.cpp
    Jolt/Physics/DeterminismLog.cpp
    Jolt/Physics/IslandBuilder.cpp
    Jolt/Physics/LargeIslandSplitter.cpp
    Jolt/Physics/PhysicsLock.cpp
    Jolt/Physics/PhysicsScene.cpp
    Jolt/Physics/PhysicsSystem.cpp
    Jolt/Physics/PhysicsUpdateContext.cpp
    Jolt/Physics/StateRecorderImpl.cpp
    Jolt/Renderer/DebugRenderer.cpp
    Jolt/Renderer/DebugRendererPlayback.cpp
    Jolt/Renderer/DebugRendererRecorder.cpp
    Jolt/Skeleton/SkeletalAnimation.cpp
    Jolt/Skeleton/Skeleton.cpp
    Jolt/Skeleton/SkeletonMapper.cpp
    Jolt/Skeleton/SkeletonPose.cpp
    Jolt/TriangleGrouper/TriangleGrouperClosestCentroid.cpp
    Jolt/TriangleGrouper/TriangleGrouperMorton.cpp
    Jolt/TriangleSplitter/TriangleSplitterBinning.cpp
    Jolt/TriangleSplitter/TriangleSplitter.cpp
    Jolt/TriangleSplitter/TriangleSplitterFixedLeafSize.cpp
    Jolt/TriangleSplitter/TriangleSplitterLongestAxis.cpp
    Jolt/TriangleSplitter/TriangleSplitterMean.cpp
    Jolt/TriangleSplitter/TriangleSplitterMorton.cpp
    Jolt/RegisterTypes.cpp

)


