# docker-mirror


# 合并文件
cat quay.io_ascend_vllm-ascend_v0.18.0-a3.tar.gz.part.* > quay.io_ascend_vllm-ascend_v0.18.0-a3.tar.gz

# 加载镜像
docker load -i quay.io_ascend_vllm-ascend_v0.18.0-a3.tar.gz
