

ckim-mbp:terraform-provider-libvirt ckim$ git diff .gitignore
diff --git a/.gitignore b/.gitignore
index f3879e37..aec863b8 100644
--- a/.gitignore
+++ b/.gitignore
@@ -6,3 +6,4 @@
 *.test
 *.cov
 terraform-provider-libvirt
+.idea
ckim-mbp:terraform-provider-libvirt ckim$ 


ckim-mbp:terraform-provider-libvirt ckim$ git diff main.go 
diff --git a/main.go b/main.go
index 7fee0a95..49e7b156 100644
--- a/main.go
+++ b/main.go
@@ -9,7 +9,7 @@ import (
        "os"
        "time"
 
-       "github.com/dmacvicar/terraform-provider-libvirt/libvirt"
+       "github.com/kimcharli/terraform-provider-libvirt/libvirt"
        "github.com/hashicorp/terraform/plugin"
        libvirtgo "github.com/libvirt/libvirt-go"
 )
ckim-mbp:terraform-provider-libvirt ckim$ 



