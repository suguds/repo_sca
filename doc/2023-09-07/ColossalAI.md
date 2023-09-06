# hpcaitech/ColossalAI安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1699486854683607040.svg)](https://www.murphysec.com/console/report/1699124457989865472/1699486854683607040)

仓库描述：Making large AI models cheaper, faster and more accessible

仓库地址：[https://github.com/hpcaitech/ColossalAI](https://github.com/hpcaitech/ColossalAI)

| star：32403 | watch：341 | fork：3763 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-06 23:42:16 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-07 02:17:15 | 组件总数：322 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|Python 安全漏洞|ReDoS|[MPS-2022-57238](https://www.oscs1024.com/hd/MPS-2022-57238)|CVE-2022-40897|中危|
|PyTorch 命令注入漏洞|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|torch|1.12|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|setuptools|39.2.0|65.5.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|numpy|1.24.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|12|Low|
|自定义许可证|10|Low|
|BSD-3-Clause|3|Low|
|BSD-2-Clause|2|Low|
|Apache-2.0|7|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|abstractmethod||间接依赖|pip|
|SentencePiece|0.1.99|间接依赖|pip|
|StatefulTensor||间接依赖|pip|
|List||间接依赖|pip|
|disable_existing_loggers||间接依赖|pip|
|titans|0.0.7|间接依赖|pip|
|fastapi|0.85.1|间接依赖|pip|
|clear_cache_before_run||间接依赖|pip|
|einsum||间接依赖|pip|
|convert_to_apex_amp||间接依赖|pip|
|Experts||间接依赖|pip|
|DuplicatedShardingDimensionError||间接依赖|pip|
|distribute_tensor||间接依赖|pip|
|model||间接依赖|pip|
|torchvision||间接依赖|pip|
|get_lr_scheduler||间接依赖|pip|
|NOT_NVML||间接依赖|pip|
|llama_load_quant||间接依赖|pip|
|convert_to_naive_amp||间接依赖|pip|
|_bool||间接依赖|pip|
|get_tensorboard_writer||间接依赖|pip|
|bias_addition_method||间接依赖|pip|
|GPT2LMHeadModel||间接依赖|pip|
|flash_attn|2.0.5|间接依赖|pip|
|assert_close_loose||间接依赖|pip|
|DynamicGradScaler||间接依赖|pip|
|check_lazy_init||间接依赖|pip|
|diffusers|0.5.0|间接依赖|pip|
|sanic_ext|22.9.0|间接依赖|pip|
|ColoGraphModule||间接依赖|pip|
|load_moe_model||间接依赖|pip|
|partition_uniform||间接依赖|pip|
|ConvModuleHandler||间接依赖|pip|
|pudb|2019.2|间接依赖|pip|
|MemoryCost||间接依赖|pip|
|Tuple||间接依赖|pip|
|get_batch_size||间接依赖|pip|
|Sequence||间接依赖|pip|
|QueueFullError||间接依赖|pip|
|Solver||间接依赖|pip|
|OUTPUT_SAVED_OPS||间接依赖|pip|
|LinearModuleHandler||间接依赖|pip|
|ConcatDataset||间接依赖|pip|
|map_arg||间接依赖|pip|
|Deque||间接依赖|pip|
|hooks||间接依赖|pip|
|chen_greedy||间接依赖|pip|
|run_on_environment_flag||间接依赖|pip|
|print_rank_0||间接依赖|pip|
|BLOOMRM||间接依赖|pip|
|colossalai|0.3.0|间接依赖|pip|
|triton|2.0.0.dev20221202|间接依赖|pip|
|Extension||间接依赖|pip|
|FusedAdam||间接依赖|pip|
|albumentations|1.3.0|间接依赖|pip|
|Iterable||间接依赖|pip|
|BLOOMActor||间接依赖|pip|
|torchrec|0.2.0|间接依赖|pip|
|ChatGLMModel||间接依赖|pip|
|split_batch_2p5d||间接依赖|pip|
|DDPMScheduler||间接依赖|pip|
|Linear||间接依赖|pip|
|AlbertConfig||间接依赖|pip|
|test-tube|0.7.5|间接依赖|pip|
|Any||间接依赖|pip|
|ParallelMode||间接依赖|pip|
|rerun_on_exception||间接依赖|pip|
|_format_time||间接依赖|pip|
|ColoTensor||间接依赖|pip|
|DDPStrategy||间接依赖|pip|
|gather_tensor||间接依赖|pip|
|T5Tokenizer||间接依赖|pip|
|GPTActor||间接依赖|pip|
|imageio-ffmpeg|0.4.2|间接依赖|pip|
|locust|2.11.0|间接依赖|pip|
|Optional||间接依赖|pip|
|bench_rotor||间接依赖|pip|
|HostInfoList||间接依赖|pip|
|ABC||间接依赖|pip|
|solver_rotor||间接依赖|pip|
|get_data||间接依赖|pip|
|CollectiveCommPattern||间接依赖|pip|
|Set||间接依赖|pip|
|_DimSpec||间接依赖|pip|
|SGD||间接依赖|pip|
|ALLGATHER_COST||间接依赖|pip|
|FFNExperts||间接依赖|pip|
|Strategy||间接依赖|pip|
|MoeLayer||间接依赖|pip|
|check_grad||间接依赖|pip|
|get_profile_context||间接依赖|pip|
|MLP||间接依赖|pip|
|OPTForCausalLM||间接依赖|pip|
|tensorboard|2.14.0|间接依赖|pip|
|convert_to_torch_amp||间接依赖|pip|
|compatibility||间接依赖|pip|
|DataLoader||间接依赖|pip|
|_device||间接依赖|pip|
|DeviceMeshManager||间接依赖|pip|
|SUPPORT_FLASH||间接依赖|pip|
|make_experience_batch||间接依赖|pip|
|get_batch_for_sequence_parallel||间接依赖|pip|
|gradio|3.34.0|间接依赖|pip|
|torch|1.12|间接依赖|pip|
|fbgemm-gpu|0.2.0|间接依赖|pip|
|ConstantGradScaler||间接依赖|pip|
|imread||间接依赖|pip|
|HfFolder||间接依赖|pip|
|HostInfo||间接依赖|pip|
|TensorState||间接依赖|pip|
|setuptools|39.2.0|间接依赖|pip|
|cast_tensor_to_fp16||间接依赖|pip|
|TPExperts||间接依赖|pip|
|einops|0.3.0|间接依赖|pip|
|BufferItem||间接依赖|pip|
|reduce_by_batch_2p5d||间接依赖|pip|
|HybridAdam||间接依赖|pip|
|register_leaf_module||间接依赖|pip|
|setup||间接依赖|pip|
|BaseProfiler||间接依赖|pip|
|beans_collator||间接依赖|pip|
|save_moe_model||间接依赖|pip|
|Repository||间接依赖|pip|
|ColoTracer||间接依赖|pip|
|NetflixDataset||间接依赖|pip|
|SUPPORT_LAZY||间接依赖|pip|
|rpc_is_initialized||间接依赖|pip|
|Lars||间接依赖|pip|
|bias_addition_function||间接依赖|pip|
|DeviceMeshInfo||间接依赖|pip|
|Lamb||间接依赖|pip|
|UNetModel||间接依赖|pip|
|Dataset||间接依赖|pip|
|ViTForImageClassification||间接依赖|pip|
|GPTLMLoss||间接依赖|pip|
|ChatGLMForConditionalGeneration||间接依赖|pip|
|coverage|7.2.3|间接依赖|pip|
|launch_engine||间接依赖|pip|
|parse_args||间接依赖|pip|
|seed||间接依赖|pip|
|uvicorn|0.19.0|间接依赖|pip|
|_create_vision_transformer||间接依赖|pip|
|OPTActor||间接依赖|pip|
|yaml||间接依赖|pip|
|ShapeProp||间接依赖|pip|
|Trainer||间接依赖|pip|
|get_cuda_cc_flag||间接依赖|pip|
|PromptDataset||间接依赖|pip|
|MemoryEfficientAttentionCutlassOp||间接依赖|pip|
|setattr_||间接依赖|pip|
|bias_dropout_add_fused_train||间接依赖|pip|
|ChatPromptProcessor||间接依赖|pip|
|palm_pytorch||间接依赖|pip|
|ShardingNotDivisibleError||间接依赖|pip|
|GraphAnalyser||间接依赖|pip|
|LowLevelZeroPlugin||间接依赖|pip|
|Image||间接依赖|pip|
|T5EncoderModel||间接依赖|pip|
|OPTCritic||间接依赖|pip|
|DropoutForParallelInput||间接依赖|pip|
|assert_close||间接依赖|pip|
|transformers|4.30.2|间接依赖|pip|
|SupervisedDataset||间接依赖|pip|
|CostGraph||间接依赖|pip|
|numpy|1.24.1|间接依赖|pip|
|scatter_tensor||间接依赖|pip|
|RmStaticDataset||间接依赖|pip|
|memory_efficient_attention||间接依赖|pip|
|EncoderUNetModel||间接依赖|pip|
|split_batch_2d||间接依赖|pip|
|OperationData||间接依赖|pip|
|Graph||间接依赖|pip|
|HiddenParallelEmbedding||间接依赖|pip|
|GPTCritic||间接依赖|pip|
|check_ABT||间接依赖|pip|
|ShardingStrategy||间接依赖|pip|
|DistSpecManager||间接依赖|pip|
|append_nvcc_threads||间接依赖|pip|
|HhRlhfDataset||间接依赖|pip|
|rpc_run||间接依赖|pip|
|check_AB||间接依赖|pip|
|PreTrainedTokenizer||间接依赖|pip|
|low_resource_init||间接依赖|pip|
|BLOOMCritic||间接依赖|pip|
|GeminiPlugin||间接依赖|pip|
|check_topo||间接依赖|pip|
|omegaconf|2.1.1|间接依赖|pip|
|replace_xformers||间接依赖|pip|
|profile||间接依赖|pip|
|CommSpec||间接依赖|pip|
|MetaInfoProp||间接依赖|pip|
|BertConfig||间接依赖|pip|
|rerun_if_address_is_in_use||间接依赖|pip|
|_pair||间接依赖|pip|
|ViTConfig||间接依赖|pip|
|find_packages||间接依赖|pip|
|lightning|1.9.0|间接依赖|pip|
|opencv-python|4.6.0.66|间接依赖|pip|
|get_current_device||间接依赖|pip|
|Tensor||间接依赖|pip|
|bias_dropout_add_fused_inference||间接依赖|pip|
|check_state_dict_equal||间接依赖|pip|
|Generator||间接依赖|pip|
|linearize||间接依赖|pip|
|ProfilerActivity||间接依赖|pip|
|get_model||间接依赖|pip|
|CPUAdam||间接依赖|pip|
|DropoutForReplicatedInput||间接依赖|pip|
|netflix_collator||间接依赖|pip|
|flash_attn_varlen_func||间接依赖|pip|
|colo_device_memory_capacity||间接依赖|pip|
|SHARD_COST||间接依赖|pip|
|sanic|22.9.0|间接依赖|pip|
|reduce_by_batch_2d||间接依赖|pip|
|SolverFactory||间接依赖|pip|
|webdataset|0.2.5|间接依赖|pip|
|get_gpt2_components||间接依赖|pip|
|ShardingSpec||间接依赖|pip|
|matmul||间接依赖|pip|
|SFTDataset||间接依赖|pip|
|DAG_MLP||间接依赖|pip|
|ModelAttribute||间接依赖|pip|
|assert_equal_in_group||间接依赖|pip|
|ChainDataset||间接依赖|pip|
|pg_parse_args||间接依赖|pip|
|custom_bwd||间接依赖|pip|
|Field||间接依赖|pip|
|SeqLenInfo||间接依赖|pip|
|ldm||间接依赖|pip|
|FillDrainPipelineEngine||间接依赖|pip|
|TorchDDPPlugin||间接依赖|pip|
|BloomTokenizerFast||间接依赖|pip|
|TensorMetadata||间接依赖|pip|
|recv_forward||间接依赖|pip|
|Iterator||间接依赖|pip|
|partition_balanced||间接依赖|pip|
|uniform_split_pass||间接依赖|pip|
|balanced_split_pass||间接依赖|pip|
|Matmul_ABT_2p5D||间接依赖|pip|
|_recv_object||间接依赖|pip|
|custom_fwd||间接依赖|pip|
|_reverse_repeat_tuple||间接依赖|pip|
|Adam||间接依赖|pip|
|AutoencoderKL||间接依赖|pip|
|ColoParameter||间接依赖|pip|
|parameterize||间接依赖|pip|
|BeansDataset||间接依赖|pip|
|streamlit|1.11.1|间接依赖|pip|
|_send_object||间接依赖|pip|
|compute_reward||间接依赖|pip|
|ConvFunctionHandler||间接依赖|pip|
|ImageDraw||间接依赖|pip|
|DataCollatorForSupervisedDataset||间接依赖|pip|
|get_timers||间接依赖|pip|
|LinearFunctionHandler||间接依赖|pip|
|nn||间接依赖|pip|
|sleep||间接依赖|pip|
|contextmanager||间接依赖|pip|
|GPT2Config||间接依赖|pip|
|split_with_split_nodes_pass||间接依赖|pip|
|Decoder||间接依赖|pip|
|dtype||间接依赖|pip|
|Repad||间接依赖|pip|
|get_dist_logger||间接依赖|pip|
|colo_set_process_memory_fraction||间接依赖|pip|
|INPUT_GROUP_3D||间接依赖|pip|
|ComputeSpec||间接依赖|pip|
|Encoder||间接依赖|pip|
|inf||间接依赖|pip|
|Dialogue||间接依赖|pip|
|cast_tensor_to_bf16||间接依赖|pip|
|spawn||间接依赖|pip|
|OperationDataType||间接依赖|pip|
|tqdm|4.61.2|间接依赖|pip|
|OneFOneBPipelineEngine||间接依赖|pip|
|Embedding||间接依赖|pip|
|open-clip-torch|2.7.0|间接依赖|pip|
|is_compatible_with_meta||间接依赖|pip|
|register_leaf_module_impl||间接依赖|pip|
|Union||间接依赖|pip|
|flash_attn_func||间接依赖|pip|
|recv_backward||间接依赖|pip|
|imsave||间接依赖|pip|
|HiddenParallelGPTLMHead1D||间接依赖|pip|
|graph_profile_pass||间接依赖|pip|
|AutoConfig||间接依赖|pip|
|nullcontext||间接依赖|pip|
|pydantic|1.10.2|间接依赖|pip|
|extract_into_tensor||间接依赖|pip|
|LowLevelZeroStrategy||间接依赖|pip|
|build_model||间接依赖|pip|
|model_zoo||间接依赖|pip|
|all_gather||间接依赖|pip|
|GeminiStrategy||间接依赖|pip|
|torchmetrics|0.7|间接依赖|pip|
|make_beta_schedule||间接依赖|pip|
|Dict||间接依赖|pip|
|SequenceParallelDataIterator||间接依赖|pip|
|ColoTensorSpec||间接依赖|pip|
|WEIGHT_GROUP_3D||间接依赖|pip|
|AlbertForSequenceClassification||间接依赖|pip|
|OUTPUT_SAVED_MOD||间接依赖|pip|
|ProcessGroup||间接依赖|pip|
|requirements.txt||间接依赖|pip|
|calc_action_log_probs||间接依赖|pip|
|BertForSequenceClassification||间接依赖|pip|
|imageio|2.9.0|间接依赖|pip|
|get_micro_batch||间接依赖|pip|
|ShapeConsistencyManager||间接依赖|pip|
|https||间接依赖|pip|
|ComputePattern||间接依赖|pip|
|Node||间接依赖|pip|
|all_reduce||间接依赖|pip|
|_cfg||间接依赖|pip|
|BaseModel||间接依赖|pip|
|getattr_||间接依赖|pip|
|Matmul_AB_2p5D||间接依赖|pip|
|AutoTokenizer||间接依赖|pip|
|broadcast||间接依赖|pip|
|packaging||间接依赖|pip|
|pandas|1.4.1|间接依赖|pip|
|Callable||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)