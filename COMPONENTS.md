# Personal Whisperer components

Only the exact GigaAM Multilingual 600M CPU INT8 ONNX adaptation used by Personal Whisperer is hosted here. Application source code, profiles, audio, keys and settings are not published. Other components are downloaded directly from their upstream providers.

Base model: https://huggingface.co/ai-sage/GigaAM-Multilingual/tree/3905cd51c3ed4e88c8edf33f3302969ba480a327

Adaptation: official large_ctc ONNX export with Sherpa metadata and dynamic MatMul/Gemm QUInt8 quantization. MIT license from the original model is included.

Artifact: gigaam-600m-ctc-int8.onnx, 835294657 bytes. SHA256: 4855fddd1e2b6f6638ab3d35158b6ee8295af173ef45feaf64e646701ebf51a4.

The conversion is provided as a pinned binary so the application needs no Python, PyTorch or ONNX conversion tools on the user computer.
