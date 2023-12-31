# pytorch/pytorch安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691877497568518144.svg)](https://www.murphysec.com/console/report/1691877496981315584/1691877497568518144)

仓库描述：Tensors and Dynamic neural networks in Python with strong GPU acceleration

仓库地址：[https://github.com/pytorch/pytorch](https://github.com/pytorch/pytorch)

| star：69795 | watch：1671 | fork：19125 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-17 02:18:42 | 许可证：- |
| 最近检测时间：2023-08-17 02:39:20 | 组件总数：493 | 漏洞总数：7 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-2018-14365|越界写入|[MPS-2018-14365](https://www.oscs1024.com/hd/MPS-2018-14365)|CVE-2018-3977|高危|
|MPS-2018-4435|越界读取|[MPS-2018-4435](https://www.oscs1024.com/hd/MPS-2018-4435)|CVE-2018-3837|中危|
|MPS-2018-4436|越界读取|[MPS-2018-4436](https://www.oscs1024.com/hd/MPS-2018-4436)|CVE-2018-3838|中危|
|MPS-2018-4437|越界写入|[MPS-2018-4437](https://www.oscs1024.com/hd/MPS-2018-4437)|CVE-2018-3839|高危|
|MPS-2021-25631|不充分的比较|[MPS-2021-25631](https://www.oscs1024.com/hd/MPS-2021-25631)|CVE-2021-34141|中危|
|MPS-2021-32278|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|MPS-2022-57238|ReDoS|[MPS-2022-57238](https://www.oscs1024.com/hd/MPS-2022-57238)|CVE-2022-40897|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|sdl_image|2.0.5||间接依赖|建议修复|C:0|H:2|M:2|L:0|
|numpy|1.22.0|1.22.2|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|setuptools|39.2.0|65.5.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|29|Low|
|MIT|28|Low|
|Apache-2.0|9|Low|
|BSD-3-Clause|7|Low|
|BSD-2-Clause|1|Low|
|MPL-2.0|1|Low|
|Apache-2.0 OR MIT|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|Enum||间接依赖|pip|
|security|0.1.3|间接依赖|bundler|
|normalize_inputs||间接依赖|pip|
|generate_methods_for_privateuse1_backend||间接依赖|pip|
|ExactWeakKeyDictionary||间接依赖|pip|
|min_cut_rematerialization_partition||间接依赖|pip|
|SubWithTorchFunction||间接依赖|pip|
|ExpandedWeight||间接依赖|pip|
|map_arg||间接依赖|pip|
|make_graph||间接依赖|pip|
|google-apis-iamcredentials_v1|0.12.0|间接依赖|bundler|
|gen_sparse_coo||间接依赖|pip|
|flake8-comprehensions|3.3.0|间接依赖|pip|
|aws-sigv4|1.5.0|间接依赖|bundler|
|ReduceOp||间接依赖|pip|
|FakeTensorMode||间接依赖|pip|
|terminal-notifier|2.0.0|间接依赖|bundler|
|_pair||间接依赖|pip|
|_len_torch_dispatch_stack||间接依赖|pip|
|word_wrap|1.0.0|间接依赖|bundler|
|Expr||间接依赖|pip|
|python-etcd|0.4.5|间接依赖|pip|
|_load_for_lite_interpreter||间接依赖|pip|
|unf_ext|0.0.8.2|间接依赖|bundler|
|all_types_and||间接依赖|pip|
|IS_MACOS||间接依赖|pip|
|faraday-httpclient|1.0.1|间接依赖|bundler|
|INIT_METHOD_TEMPLATE||间接依赖|pip|
|bottleneck||间接依赖|pip|
|bundler||间接依赖|bundler|
|__allow_nonbracketed_mutation||间接依赖|pip|
|rnn_cell||间接依赖|pip|
|out_dims_t||间接依赖|pip|
|_rename_privateuse1_backend||间接依赖|pip|
|_batch_mahalanobis||间接依赖|pip|
|_flatten_dense_tensors||间接依赖|pip|
|tqdm|4.64.0|间接依赖|pip|
|troldal-zippy|cci.20200622|间接依赖||
|Dispatcher||间接依赖|pip|
|datasets||间接依赖|pip|
|get_tests||间接依赖|pip|
|ETKernelIndex||间接依赖|pip|
|_get_privateuse1_backend_name||间接依赖|pip|
|google-cloud-core|1.6.0|间接依赖|bundler|
|faraday-rack|1.0.0|间接依赖|bundler|
|reduce_scatter||间接依赖|pip|
|Event||间接依赖|pip|
|PassResult||间接依赖|pip|
|webrick|1.7.0|间接依赖|bundler|
|BackendConfig||间接依赖|pip|
|core||间接依赖|pip|
|faraday-net_http_persistent|1.2.0|间接依赖|bundler|
|do_bench||间接依赖|pip|
|metanet_pb2||间接依赖|pip|
|get_commit_data_cache||间接依赖|pip|
|float_to_apot||间接依赖|pip|
|patch||间接依赖|pip|
|sphinxcontrib.katex|0.8.6|间接依赖|pip|
|varlen_pytorch_lstm_creator||间接依赖|pip|
|FakeTensor||间接依赖|pip|
|Variable||间接依赖|pip|
|ProfilerActivity||间接依赖|pip|
|broadcast_all||间接依赖|pip|
|given||间接依赖|pip|
|_prepare_video||间接依赖|pip|
|clamp_probs||间接依赖|pip|
|retriable|3.1.2|间接依赖|bundler|
|IterDataPipe||间接依赖|pip|
|ExportArgs||间接依赖|pip|
|OperatorName||间接依赖|pip|
|Real||间接依赖|pip|
|exhale|0.2.3|间接依赖|pip|
|no_type_check||间接依赖|pip|
|SummaryWriter||间接依赖|pip|
|model_helper||间接依赖|pip|
|pad||间接依赖|pip|
|com.android.support:appcompat-v7|28.0.0|直接依赖|maven|
|Tensor||间接依赖|pip|
|CompileSpec||间接依赖|pip|
|TestCase||间接依赖|pip|
|Hardswish||间接依赖|pip|
|BertLMPredictionHead||间接依赖|pip|
|argument_type||间接依赖|pip|
|abspath||间接依赖|pip|
|NoReturn||间接依赖|pip|
|mini_mime|1.1.2|间接依赖|bundler|
|fake||间接依赖|pip|
|reset||间接依赖|pip|
|create_folder||间接依赖|pip|
|namedtuple||间接依赖|pip|
|flake8-executable|2.0.4|间接依赖|pip|
|use_aten_gemm_kernels||间接依赖|pip|
|flake8|3.8.2|间接依赖|pip|
|from_markdown_table||间接依赖|pip|
|toleranceOverride||间接依赖|pip|
|collate_sentences_lm||间接依赖|pip|
|collate_wrapper_criteo_offset||间接依赖|pip|
|addmm_epilogue||间接依赖|pip|
|lru_cache||间接依赖|pip|
|Literal||间接依赖|pip|
|babosa|1.0.4|间接依赖|bundler|
|is_dataclass||间接依赖|pip|
|BooleanAtom||间接依赖|pip|
|randperm||间接依赖|pip|
|Dict||间接依赖|pip|
|flake8-pyi|20.5.0|间接依赖|pip|
|symbolic_opset9||间接依赖|pip|
|tensorboard|2.10.0|间接依赖|pip|
|com.facebook.soloader:nativeloader|0.10.5|直接依赖|maven|
|PassBase||间接依赖|pip|
|DispatchKey||间接依赖|pip|
|DefaultDict||间接依赖|pip|
|inf||间接依赖|pip|
|Location||间接依赖|pip|
|cnn||间接依赖|pip|
|Summary||间接依赖|pip|
|google-apis-playcustomapp_v1|0.9.0|间接依赖|bundler|
|Set||间接依赖|pip|
|Categorical||间接依赖|pip|
|google-cloud-errors|1.2.0|间接依赖|bundler|
|FunctionSchema||间接依赖|pip|
|BenchmarkLMDataset||间接依赖|pip|
|AttrSource||间接依赖|pip|
|forward_helper||间接依赖|pip|
|tty-spinner|0.9.3|间接依赖|bundler|
|_maximize_doc||间接依赖|pip|
|SequentialSampler||间接依赖|pip|
|get_tool_path_by_platform||间接依赖|pip|
|Popen||间接依赖|pip|
|contextmanager||间接依赖|pip|
|create_bandwidth_info_str||间接依赖|pip|
|constraints||间接依赖|pip|
|CriteoDataset||间接依赖|pip|
|Tuple||间接依赖|pip|
|load_metric||间接依赖|pip|
|grad||间接依赖|pip|
|all_gather||间接依赖|pip|
|google-cloud-storage|1.36.2|间接依赖|bundler|
|faraday-em_synchrony|1.0.0|间接依赖|bundler|
|dataset||间接依赖|pip|
|fields||间接依赖|pip|
|faraday-retry|1.0.3|间接依赖|bundler|
|default_generator||间接依赖|pip|
|make_node||间接依赖|pip|
|_add_docstr||间接依赖|pip|
|NamedTuple||间接依赖|pip|
|rename_privateuse1_backend||间接依赖|pip|
|faraday-multipart|1.0.4|间接依赖|bundler|
|Benchmark||间接依赖|pip|
|tvm_compile||间接依赖|pip|
|PowerTransform||间接依赖|pip|
|softplus||间接依赖|pip|
|faraday-excon|1.1.0|间接依赖|bundler|
|IO||间接依赖|pip|
|grad_and_value||间接依赖|pip|
|PIPE||间接依赖|pip|
|benchmark_core||间接依赖|pip|
|numpy|1.22.0|间接依赖|pip|
|http-cookie|1.0.5|间接依赖|bundler|
|FileWriter||间接依赖|pip|
|ModuleList||间接依赖|pip|
|_export_operator_list||间接依赖|pip|
|pytorch_lstm_creator||间接依赖|pip|
|dirname||间接依赖|pip|
|xcpretty-travis-formatter|1.0.1|间接依赖|bundler|
|google-apis-storage_v1|0.16.0|间接依赖|bundler|
|HealthCheck||间接依赖|pip|
|defaultdict||间接依赖|pip|
|_fft||间接依赖|pip|
|httpclient|2.8.3|间接依赖|bundler|
|dist_init||间接依赖|pip|
|TensorKey||间接依赖|pip|
|matplotlib|3.6.0|间接依赖|pip|
|OrderedDict||间接依赖|pip|
|dyndep||间接依赖|pip|
|asdict||间接依赖|pip|
|caffe2||间接依赖|pip|
|UninitializedParameter||间接依赖|pip|
|upload_file_to_s3||间接依赖|pip|
|json|2.6.2|间接依赖|bundler|
|OpOverloadPacket||间接依赖|pip|
|representable|3.2.0|间接依赖|bundler|
|CALLABLE_NODE_OPS||间接依赖|pip|
|topics||间接依赖|pip|
|get_decompositions||间接依赖|pip|
|abstractmethod||间接依赖|pip|
|summarize_test_cases||间接依赖|pip|
|conv_args_and_kwargs||间接依赖|pip|
|colored2|3.1.2|间接依赖|bundler|
|xcodeproj|1.22.0|间接依赖|bundler|
|memonger||间接依赖|pip|
|multi_json|1.15.0|间接依赖|bundler|
|ModuleType||间接依赖|pip|
|FuzzedTensor||间接依赖|pip|
|xcpretty|0.3.0|间接依赖|bundler|
|List||间接依赖|pip|
|wraps||间接依赖|pip|
|_standard_normal||间接依赖|pip|
|Net||间接依赖|pip|
|CoreMLComputeUnit||间接依赖|pip|
|currentframe||间接依赖|pip|
|gcc_coverage||间接依赖|pip|
|functional_call||间接依赖|pip|
|cpuinfo|cci.20201217|间接依赖||
|GetItemSource||间接依赖|pip|
|field||间接依赖|pip|
|ABC||间接依赖|pip|
|ReLU6||间接依赖|pip|
|run_cpp_test||间接依赖|pip|
|defake||间接依赖|pip|
|unicode-display_width|1.8.0|间接依赖|bundler|
|TritonTemplate||间接依赖|pip|
|export_case||间接依赖|pip|
|tty-screen|0.8.1|间接依赖|bundler|
|Jinja2|3.1.0|间接依赖|pip|
|Importer||间接依赖|pip|
|conv_backward||间接依赖|pip|
|torchgen||间接依赖|pip|
|capture_logs||间接依赖|pip|
|to_markdown_table||间接依赖|pip|
|nanaimo|0.3.0|间接依赖|bundler|
|faraday-em_http|1.0.0|间接依赖|bundler|
|Boolean||间接依赖|pip|
|assume||间接依赖|pip|
|hypothesis||间接依赖|pip|
|tol||间接依赖|pip|
|com.facebook.fbjni:fbjni-java-only|0.2.2|直接依赖|maven|
|caffe2_pb2||间接依赖|pip|
|trailblazer-option|0.1.2|间接依赖|bundler|
|google-cloud-env|1.6.0|间接依赖|bundler|
|ceildiv||间接依赖|pip|
|config||间接依赖|pip|
|Graph||间接依赖|pip|
|tty-cursor|0.7.1|间接依赖|bundler|
|_ExcludeDispatchKeyGuard||间接依赖|pip|
|DFIterDataPipe||间接依赖|pip|
|NativeFunction||间接依赖|pip|
|deferred_init||间接依赖|pip|
|unf|0.1.4|间接依赖|bundler|
|docutils|0.16|间接依赖|pip|
|_reductions_impl||间接依赖|pip|
|partial||间接依赖|pip|
|convert_to_HWC||间接依赖|pip|
|myst-parser|0.18.1|间接依赖|pip|
|Function||间接依赖|pip|
|tree_flatten||间接依赖|pip|
|os|1.1.4|间接依赖|bundler|
|SubTensor||间接依赖|pip|
|excon|0.92.3|间接依赖|bundler|
|device_from_inputs||间接依赖|pip|
|deque||间接依赖|pip|
|aws-sdk-kms|1.57.0|间接依赖|bundler|
|Node||间接依赖|pip|
|checkpoint||间接依赖|pip|
|sympy_product||间接依赖|pip|
|colored|1.2|间接依赖|bundler|
|LocalSource||间接依赖|pip|
|symbolic_helper||间接依赖|pip|
|terminal-table|1.8.0|间接依赖|bundler|
|is_lazy_module||间接依赖|pip|
|Iterator||间接依赖|pip|
|register_debug_backend||间接依赖|pip|
|compiled_function||间接依赖|pip|
|group||间接依赖|pip|
|utils||间接依赖|pip|
|fqn_to_module||间接依赖|pip|
|aws-sdk-s3|1.114.0|间接依赖|bundler|
|ModuleDict||间接依赖|pip|
|cast||间接依赖|pip|
|google-apis-core|0.6.0|间接依赖|bundler|
|mccabe|0.6.1|间接依赖|pip|
|SupportLevel||间接依赖|pip|
|apot_to_float||间接依赖|pip|
|_Faketqdm||间接依赖|pip|
|PackageExporter||间接依赖|pip|
|_pytest||间接依赖|pip|
|torch||间接依赖|pip|
|get_gcda_files||间接依赖|pip|
|declarative|0.0.20|间接依赖|bundler|
|has_no_children_ignoring_parametrizations||间接依赖|pip|
|workspace||间接依赖|pip|
|Iterable||间接依赖|pip|
|Deque||间接依赖|pip|
|com.facebook.soloader:nativeloader|0.10.1|直接依赖|maven|
|jmespath|1.6.1|间接依赖|bundler|
|rouge|2.0.7|间接依赖|bundler|
|memoist|0.16.2|间接依赖|bundler|
|GeneratorStateSource||间接依赖|pip|
|TEST_WITH_ROCM||间接依赖|pip|
|closing||间接依赖|pip|
|triton||间接依赖|pip|
|Optional||间接依赖|pip|
|allowed_functions||间接依赖|pip|
|logits_to_probs||间接依赖|pip|
|ExportCase||间接依赖|pip|
|tree_map||间接依赖|pip|
|Number||间接依赖|pip|
|Conv2d||间接依赖|pip|
|pt||间接依赖|pip|
|claide|1.1.0|间接依赖|bundler|
|test_util||间接依赖|pip|
|atomos|0.1.3|间接依赖|bundler|
|FuzzedParameter||间接依赖|pip|
|brew||间接依赖|pip|
|flake8-bugbear|20.1.4|间接依赖|pip|
|counters||间接依赖|pip|
|faraday-patron|1.0.0|间接依赖|bundler|
|parse_args||间接依赖|pip|
|standard_kwargs||间接依赖|pip|
|sphinx_copybutton|0.3.1|间接依赖|pip|
|Conv1d||间接依赖|pip|
|multipart-post|2.0.0|间接依赖|bundler|
|schema||间接依赖|pip|
|multipledispatch||间接依赖|pip|
|IS_WINDOWS||间接依赖|pip|
|dequantize_APoT||间接依赖|pip|
|CFPropertyList|3.0.5|间接依赖|bundler|
|quantize_APoT||间接依赖|pip|
|faraday-cookie_jar|0.0.7|间接依赖|bundler|
|return_type||间接依赖|pip|
|TYPE_CHECKING||间接依赖|pip|
|naturally|2.2.1|间接依赖|bundler|
|breathe|4.25.0|间接依赖|pip|
|run||间接依赖|pip|
|ExpTransform||间接依赖|pip|
|IPython|8.12.0|间接依赖|pip|
|RRef||间接依赖|pip|
|CallFunction||间接依赖|pip|
|google-apis-androidpublisher_v3|0.23.0|间接依赖|bundler|
|_single||间接依赖|pip|
|is_rref||间接依赖|pip|
|optparse|0.1.1|间接依赖|bundler|
|autotune_select_algorithm||间接依赖|pip|
|MapDataPipe||间接依赖|pip|
|sphinx-copybutton|0.5.0|间接依赖|pip|
|use_triton_template||间接依赖|pip|
|Target||间接依赖|pip|
|auto||间接依赖|pip|
|get_raw_profiles_folder||间接依赖|pip|
|_LazyNormBase||间接依赖|pip|
|requirements.txt||间接依赖|pip|
|rake|13.0.6|间接依赖|bundler|
|nullcontext||间接依赖|pip|
|pycodestyle|2.6.0|间接依赖|pip|
|nan||间接依赖|pip|
|ruby2_keywords|0.0.5|间接依赖|bundler|
|mm_args||间接依赖|pip|
|deepcopy||间接依赖|pip|
|Integer||间接依赖|pip|
|comptime||间接依赖|pip|
|ir||间接依赖|pip|
|impl||间接依赖|pip|
|_get_debug_info||间接依赖|pip|
|Counter||间接依赖|pip|
|inference_graph||间接依赖|pip|
|Parameter||间接依赖|pip|
|DTypeConfig||间接依赖|pip|
|CodeType||间接依赖|pip|
|FunctionType||间接依赖|pip|
|BertLayer||间接依赖|pip|
|aws-sdk-core|3.131.2|间接依赖|bundler|
|MethodDispatcher||间接依赖|pip|
|sphinx|3.5.4|间接依赖|pip|
|SimpleAddModule||间接依赖|pip|
|get_node_target||间接依赖|pip|
|NonCallableMock||间接依赖|pip|
|AffineTransform||间接依赖|pip|
|lazy_property||间接依赖|pip|
|xnnpack||间接依赖||
|aws-eventstream|1.2.0|间接依赖|bundler|
|tree_unflatten||间接依赖|pip|
|mini_magick|4.11.0|间接依赖|bundler|
|default_args||间接依赖|pip|
|jwt|2.4.1|间接依赖|bundler|
|add_tensors_loop||间接依赖|pip|
|Optimizer||间接依赖|pip|
|load_dataset||间接依赖|pip|
|ContextManager||间接依赖|pip|
|HistogramProto||间接依赖|pip|
|basename||间接依赖|pip|
|module_to_fqn||间接依赖|pip|
|rubyzip|2.3.2|间接依赖|bundler|
|_funcs_impl||间接依赖|pip|
|OrderedImporter||间接依赖|pip|
|aot_function||间接依赖|pip|
|Arg||间接依赖|pip|
|lookup_backend||间接依赖|pip|
|ETKernelKey||间接依赖|pip|
|reduce||间接依赖|pip|
|emoji_regex|3.2.3|间接依赖|bundler|
|inductor_prims||间接依赖|pip|
|OpOverload||间接依赖|pip|
|TensorPipeRpcBackendOptions||间接依赖|pip|
|Generic||间接依赖|pip|
|floating_types||间接依赖|pip|
|settings||间接依赖|pip|
|clang_coverage||间接依赖|pip|
|gh_inspector|1.1.3|间接依赖|bundler|
|fastlane|2.206.2|间接依赖|bundler|
|digest-crc|0.6.4|间接依赖|bundler|
|Library||间接依赖|pip|
|sdl_image|2.0.5|间接依赖||
|Fuzzer||间接依赖|pip|
|fuzzy_and||间接依赖|pip|
|CppExtension||间接依赖|pip|
|simctl|1.6.8|间接依赖|bundler|
|signet|0.17.0|间接依赖|bundler|
|BinaryIO||间接依赖|pip|
|_type||间接依赖|pip|
|faraday_middleware|1.2.0|间接依赖|bundler|
|fake_tensor_unsupported||间接依赖|pip|
|LoggingTensorMode||间接依赖|pip|
|_linalg||间接依赖|pip|
|PackageImporter||间接依赖|pip|
|core_aten_decompositions||间接依赖|pip|
|faraday-net_http|1.0.1|间接依赖|bundler|
|Argument||间接依赖|pip|
|setuptools|39.2.0|间接依赖|pip|
|nn||间接依赖|pip|
|_get_dispatch_stack_at||间接依赖|pip|
|flake8-logging-format|0.9.0|间接依赖|pip|
|miniz|2.1.0|间接依赖||
|allclose||间接依赖|pip|
|ContextProp||间接依赖|pip|
|transforms||间接依赖|pip|
|commander|4.6.0|间接依赖|bundler|
|make_functional||间接依赖|pip|
|Sequence||间接依赖|pip|
|BaseType||间接依赖|pip|
|layer_model_instantiator||间接依赖|pip|
|Match||间接依赖|pip|
|_special||间接依赖|pip|
|the||间接依赖|pip|
|faraday|1.10.0|间接依赖|bundler|
|BaseTy||间接依赖|pip|
|fuzzy_not||间接依赖|pip|
|in_dims_t||间接依赖|pip|
|Generator||间接依赖|pip|
|compiled_module||间接依赖|pip|
|map_aggregate||间接依赖|pip|
|inplace_methods||间接依赖|pip|
|register_replacement||间接依赖|pip|
|myst-nb|0.13.2|间接依赖|pip|
|Any||间接依赖|pip|
|equal||间接依赖|pip|
|sphinx-panels|0.4.1|间接依赖|pip|
|chain||间接依赖|pip|
|Future||间接依赖|pip|
|implements_per_sample_grads||间接依赖|pip|
|hence||间接依赖|pip|
|convert_frame||间接依赖|pip|
|download_gha_artifacts||间接依赖|pip|
|fastimage|2.2.6|间接依赖|bundler|
|googleauth|1.2.0|间接依赖|bundler|
|Mapping||间接依赖|pip|
|plist|3.6.0|间接依赖|bundler|
|GraphModule||间接依赖|pip|
|product||间接依赖|pip|
|Size||间接依赖|pip|
|profile||间接依赖|pip|
|Action||间接依赖|pip|
|getframeinfo||间接依赖|pip|
|magic_methods||间接依赖|pip|
|highline|2.0.3|间接依赖|bundler|
|torchvision||间接依赖|pip|
|dotenv|2.7.6|间接依赖|bundler|
|check_error||间接依赖|pip|
|_take_tensors||间接依赖|pip|
|_NormBase||间接依赖|pip|
|domain_name|0.5.20190701|间接依赖|bundler|
|_cuda||间接依赖|pip|
|BlobReference||间接依赖|pip|
|aws-partitions|1.601.0|间接依赖|bundler|
|public_suffix|4.0.7|间接依赖|bundler|
|cudart||间接依赖|pip|
|Union||间接依赖|pip|
|artifactory|3.0.15|间接依赖|bundler|
|_batch_mv||间接依赖|pip|
|ProcessPoolExecutor||间接依赖|pip|
|xnnpack|cci.20210310|间接依赖||
|uber|0.1.0|间接依赖|bundler|
|rexml|3.2.5|间接依赖|bundler|
|get_qparam_dict||间接依赖|pip|
|TEST_SCIPY||间接依赖|pip|
|TypeVar||间接依赖|pip|
|pyflakes|2.2.0|间接依赖|pip|
|BuildExtension||间接依赖|pip|
|Sampler||间接依赖|pip|
|dataclass||间接依赖|pip|
|Callable||间接依赖|pip|
|run_oss_python_test||间接依赖|pip|
|skip_but_pass_in_sandcastle_if||间接依赖|pip|
|addressable|2.8.0|间接依赖|bundler|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)