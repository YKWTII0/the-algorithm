scala_library(
    sources = ["*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    strict_deps = True,
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/com/twitter/storehaus:core",
        "3rdparty/jvm/javax/inject:javax.inject",
        "3rdparty/src/jvm/com/twitter/storehaus:core",
        "ann/src/main/scala/com/twitter/ann/hnsw",
        "ann/src/main/thrift/com/twitter/ann/common:ann-common-scala",
        "configapi/configapi-core",
        "content-recommender/thrift/src/main/thrift:thrift-scala",
        "cr-mixer/server/src/main/scala/com/twitter/cr_mixer/blender",
        "cr-mixer/server/src/main/scala/com/twitter/cr_mixer/config",
        "cr-mixer/server/src/main/scala/com/twitter/cr_mixer/filter",
        "cr-mixer/server/src/main/scala/com/twitter/cr_mixer/logging",
        "cr-mixer/server/src/main/scala/com/twitter/cr_mixer/model",
        "cr-mixer/server/src/main/scala/com/twitter/cr_mixer/param",
        "cr-mixer/server/src/main/scala/com/twitter/cr_mixer/param/decider",
        "cr-mixer/server/src/main/scala/com/twitter/cr_mixer/ranker",
        "cr-mixer/server/src/main/scala/com/twitter/cr_mixer/similarity_engine",
        "cr-mixer/server/src/main/scala/com/twitter/cr_mixer/source_signal",
        "cr-mixer/server/src/main/scala/com/twitter/cr_mixer/util",
        "cr-mixer/thrift/src/main/thrift:thrift-scala",
        "cuad/projects/hashspace/thrift:thrift-scala",
        "decider/src/main/scala",
        "finatra/inject/inject-core/src/main/scala",
        "follow-recommendations-service/thrift/src/main/thrift:thrift-scala",
        "frigate/frigate-common:base",
        "frigate/frigate-common/src/main/scala/com/twitter/frigate/common/base",
        "frigate/frigate-common/src/main/scala/com/twitter/frigate/common/candidate",
        "frigate/frigate-common/src/main/scala/com/twitter/frigate/common/util:stats_util",
        "hermit/hermit-core/src/main/scala/com/twitter/hermit/constants",
        "hermit/hermit-core/src/main/scala/com/twitter/hermit/model",
        "simclusters-ann/thrift/src/main/thrift:thrift-scala",
        "snowflake/src/main/scala/com/twitter/snowflake/id",
        "src/scala/com/twitter/cortex/ml/embeddings/common:Helpers",
        "src/scala/com/twitter/ml/featurestore/lib",
        "src/scala/com/twitter/simclusters_v2/common",
        "src/thrift/com/twitter/frigate/data_pipeline/scalding:blue_verified_annotations-scala",
        "src/thrift/com/twitter/ml/api:embedding-scala",
        "src/thrift/com/twitter/recos/user_tweet_graph:user_tweet_graph-scala",
        "src/thrift/com/twitter/recos/user_tweet_graph_plus:user_tweet_graph_plus-scala",
        "src/thrift/com/twitter/search:earlybird-scala",
        "src/thrift/com/twitter/search/query_interaction_graph/service:qig-service-scala",
        "src/thrift/com/twitter/simclusters_v2:simclusters_v2-thrift-scala",
        "src/thrift/com/twitter/wtf/candidate:wtf-candidate-scala",
        "strato/config/columns/cuad/hashspace:hashspace-strato-client",
    ],
)
