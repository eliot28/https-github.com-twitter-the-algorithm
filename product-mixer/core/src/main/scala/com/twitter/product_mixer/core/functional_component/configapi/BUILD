scala_library(
    sources = ["*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    platform = "java8",
    strict_deps = True,
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/javax/inject:javax.inject",
        "configapi/configapi-core",
        "configapi/configapi-featureswitches:v2",
        "featureswitches/featureswitches-core",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/functional_component/configapi/registry",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/model/marshalling/request",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/product/registry",
    ],
    exports = [
        "3rdparty/jvm/javax/inject:javax.inject",
        "configapi/configapi-core",
        "configapi/configapi-featureswitches:v2",
        "featureswitches/featureswitches-core",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/functional_component/configapi/registry",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/model/marshalling/request",
        "product-mixer/core/src/main/scala/com/twitter/product_mixer/core/product/registry",
    ],
)
