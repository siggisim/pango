load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_bazel_rules_go",
    urls = ["https://github.com/bazelbuild/rules_go/releases/download/0.12.1/rules_go-0.12.1.tar.gz"],
    sha256 = "8b68d0630d63d95dacc0016c3bb4b76154fe34fca93efd65d1c366de3fcb4294",
)

load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains")

go_rules_dependencies()

go_register_toolchains()

http_archive(
    name = "bazel_gazelle",
    urls = ["https://github.com/bazelbuild/bazel-gazelle/releases/download/0.12.0/bazel-gazelle-0.12.0.tar.gz"],
    sha256 = "ddedc7aaeb61f2654d7d7d4fd7940052ea992ccdb031b8f9797ed143ac7e8d43",
)

load("@bazel_gazelle//:deps.bzl", "gazelle_dependencies", "go_repository")

gazelle_dependencies()

go_repository(
    name = "com_github_armon_go_metrics",
    commit = "783273d703149aaeb9897cf58613d5af48861c25",
    importpath = "github.com/armon/go-metrics",
)

go_repository(
    name = "com_github_dimfeld_httppath",
    commit = "ee938bf735983d53694d79138ad9820efff94c92",
    importpath = "github.com/dimfeld/httppath",
)

go_repository(
    name = "com_github_dimfeld_httptreemux",
    commit = "a454a10de4a11f751681a0914461ab9e98c2a3ff",
    importpath = "github.com/dimfeld/httptreemux",
)

go_repository(
    name = "com_github_goadesign_goa",
    commit = "4232a4069ac75fc357027b58da0266f557e49cac",
    importpath = "github.com/goadesign/goa",
)

go_repository(
    name = "com_github_hashicorp_go_immutable_radix",
    commit = "7f3cd4390caab3250a57f30efdb2a65dd7649ecf",
    importpath = "github.com/hashicorp/go-immutable-radix",
)

go_repository(
    name = "com_github_hashicorp_golang_lru",
    commit = "0fb14efe8c47ae851c0034ed7a448854d3d34cf3",
    importpath = "github.com/hashicorp/golang-lru",
)

go_repository(
    name = "com_github_inconshreveable_mousetrap",
    commit = "76626ae9c91c4f2a10f34cad8ce83ea42c93bb75",
    importpath = "github.com/inconshreveable/mousetrap",
)

go_repository(
    name = "com_github_manveru_faker",
    commit = "9fbc68a78c4dbc7914e1a23f88f126bea4383b97",
    importpath = "github.com/manveru/faker",
)

go_repository(
    name = "com_github_satori_go_uuid",
    commit = "f58768cc1a7a7e77a3bd49e98cdd21419399b6a3",
    importpath = "github.com/satori/go.uuid",
)

go_repository(
    name = "com_github_spf13_cobra",
    commit = "f2b07da1e2c38d5f12845a4f607e2e1018cbb1f5",
    importpath = "github.com/spf13/cobra",
)

go_repository(
    name = "com_github_spf13_pflag",
    commit = "2e9d26c8c37aae03e3f9d4e90b7116f5accb7cab",
    importpath = "github.com/spf13/pflag",
)

go_repository(
    name = "com_github_zach_klippenstein_goregen",
    commit = "795b5e3961ea1912fde60af417ad85e86acc0d6a",
    importpath = "github.com/zach-klippenstein/goregen",
)

go_repository(
    name = "org_golang_x_net",
    commit = "db08ff08e8622530d9ed3a0e8ac279f6d4c02196",
    importpath = "golang.org/x/net",
)
