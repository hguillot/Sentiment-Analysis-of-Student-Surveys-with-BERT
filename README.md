DEPOIS


ResourceExhaustedError:  OOM when allocating tensor with shape[2048,768] and type float on /job:localhost/replica:0/task:0/device:GPU:0 by allocator GPU_0_bfc
	 [[node model_29/transformer_encoder_29/transformer/layer_11/self_attention/query/einsum/Einsum (defined at /usr/local/lib/python3.7/dist-packages/official/nlp/modeling/layers/attention.py:432) ]]
Hint: If you want to see a list of allocated tensors when OOM happens, add report_tensor_allocations_upon_oom to RunOptions for current allocation info.
 [Op:__inference_train_function_699069]

Errors may have originated from an input operation.
Input Source operations connected to node model_29/transformer_encoder_29/transformer/layer_11/self_attention/query/einsum/Einsum:
 model_29/transformer_encoder_29/transformer/layer_10/output_layer_norm/batchnorm/add_1 (defined at /usr/local/lib/python3.7/dist-packages/official/nlp/modeling/layers/transformer.py:229)
