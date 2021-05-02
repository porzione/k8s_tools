# Kubernetes tools

`k8s_edit_secret` - fetch secret, execute local editor (EDITOR/VISUAL/xdg-open) and apply the result, auto decode/encode base64 value. Can also edit local secret file.

`k8s_edit_secret -s mysecret`

`k8s_view_secrets` - just print secret to stdout.

`k8s_view_secrets` mysecret

`k8s_patch_deployment` - patch deployment(s) from yaml without changing container image.

`k8s_patch_deployment deployment-1.yaml deployment-2.yaml`
