# onnxruntime-mirror

Unmodified copies of the static ONNX Runtime archives that the Lucidos build downloads, kept so a build does not depend on one third-party host.

Each release holds the archives for one ONNX Runtime version, named as upstream. The Lucidos build checks every download against a SHA-256 pinned in its source tree, so a file here that differs from upstream is rejected.

See ADR 0595 in lucidos-dev/lucidos. Do not use these archives for anything else.
