---
type: community
cohesion: 0.07
members: 52
---

# test_image_vision.py

**Cohesion:** 0.07 - loosely connected
**Members:** 52 nodes

## Members
- [[.b64()]] - code - graphify/llm.py
- [[.bedrock_format()]] - code - graphify/llm.py
- [[A corpus with one raster image, one svg (text), and one markdown doc.]] - rationale - tests/test_image_vision.py
- [[A single image destined for a vision request.      `raw` is None when the image]] - rationale - graphify/llm.py
- [[Build `_ImageRef`s for raster images.      `read_bytes=True` (base64 backends) l]] - rationale - graphify/llm.py
- [[Build the Anthropic `messages.content` value (str, or block list with images).]] - rationale - graphify/llm.py
- [[Build the Bedrock Converse user content list (raw bytes, not base64).]] - rationale - graphify/llm.py
- [[Build the OpenAI-compatible user `content` value (str, or part list with images)]] - rationale - graphify/llm.py
- [[Call AWS Bedrock via boto3 Converse API using the standard AWS credential chain.]] - rationale - graphify/llm.py
- [[Return refs with pixel data dropped (for non-vision backends).]] - rationale - graphify/llm.py
- [[Split a chunk into (text-like units, raster-image files).      A ``FileSlice`` i]] - rationale - graphify/llm.py
- [[Tests for image-vision support across the direct extraction backends.  Covers th]] - rationale - tests/test_image_vision.py
- [[Text block listing the images so the model emits one node per image.      Always]] - rationale - graphify/llm.py
- [[Whether `backend`'s configured model can see images.      Ollama is special-case]] - rationale - graphify/llm.py
- [[_ImageRef]] - code - graphify/llm.py
- [[_anthropic_content()]] - code - graphify/llm.py
- [[_backend_supports_vision()]] - code - graphify/llm.py
- [[_bedrock_content()]] - code - graphify/llm.py
- [[_build_image_refs()]] - code - graphify/llm.py
- [[_call_bedrock()]] - code - graphify/llm.py
- [[_fake_anthropic()]] - code - tests/test_image_vision.py
- [[_fake_boto3()]] - code - tests/test_image_vision.py
- [[_fake_openai()]] - code - tests/test_image_vision.py
- [[_image_notes()]] - code - graphify/llm.py
- [[_make_corpus()_2]] - code - tests/test_image_vision.py
- [[_openai_content()]] - code - graphify/llm.py
- [[_partition_semantic_files()]] - code - graphify/llm.py
- [[_strip_pixels()]] - code - graphify/llm.py
- [[_with_image_notes()]] - code - graphify/llm.py
- [[test_anthropic_content_has_base64_block()]] - code - tests/test_image_vision.py
- [[test_bedrock_content_uses_raw_bytes()]] - code - tests/test_image_vision.py
- [[test_build_image_refs_drops_oversized()]] - code - tests/test_image_vision.py
- [[test_build_image_refs_sets_rel_media_and_bytes()]] - code - tests/test_image_vision.py
- [[test_build_image_refs_skips_out_of_root_symlink()]] - code - tests/test_image_vision.py
- [[test_builders_fall_back_to_string_without_pixels()]] - code - tests/test_image_vision.py
- [[test_call_bedrock_sends_raw_image_bytes()]] - code - tests/test_image_vision.py
- [[test_call_claude_sends_image_block()]] - code - tests/test_image_vision.py
- [[test_call_openai_compat_sends_image_url()]] - code - tests/test_image_vision.py
- [[test_call_openai_compat_text_only_without_images()]] - code - tests/test_image_vision.py
- [[test_capability_flags()]] - code - tests/test_image_vision.py
- [[test_claude_cli_adds_dir_and_read_instruction()]] - code - tests/test_image_vision.py
- [[test_claude_cli_passes_oversized_image_by_path()]] - code - tests/test_image_vision.py
- [[test_extract_files_direct_gates_pixels_by_capability()]] - code - tests/test_image_vision.py
- [[test_image_vision.py]] - code - tests/test_image_vision.py
- [[test_no_images_is_byte_identical()]] - code - tests/test_image_vision.py
- [[test_non_pdf_still_read_as_plain_text()]] - code - tests/test_image_vision.py
- [[test_openai_content_has_data_uri()]] - code - tests/test_image_vision.py
- [[test_partition_splits_raster_from_text()]] - code - tests/test_image_vision.py
- [[test_path_backend_skips_byte_read_and_size_cap()]] - code - tests/test_image_vision.py
- [[test_pdf_is_not_treated_as_vision_image()]] - code - tests/test_image_vision.py
- [[test_pdf_routed_through_pypdf_not_readtext()]] - code - tests/test_image_vision.py
- [[test_read_files_skips_out_of_root_symlink()]] - code - tests/test_image_vision.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_image_visionpy
SORT file.name ASC
```

## Connections to other communities
- 18 edges to [[_COMMUNITY_llm.py]]
- 7 edges to [[_COMMUNITY_test_llm_backends.py]]
- 4 edges to [[_COMMUNITY_test_file_slice.py]]
- 4 edges to [[_COMMUNITY__extraction_system]]
- 4 edges to [[_COMMUNITY__call_claude_cli]]
- 4 edges to [[_COMMUNITY__call_openai_compat]]
- 2 edges to [[_COMMUNITY_test_chunking.py]]
- 1 edge to [[_COMMUNITY_test_detect.py]]
- 1 edge to [[_COMMUNITY__call_llm]]
- 1 edge to [[_COMMUNITY__parse_llm_json]]

## Top bridge nodes
- [[_ImageRef]] - degree 16, connects to 5 communities
- [[_call_bedrock()]] - degree 10, connects to 5 communities
- [[_partition_semantic_files()]] - degree 8, connects to 4 communities
- [[test_image_vision.py]] - degree 30, connects to 3 communities
- [[_build_image_refs()]] - degree 19, connects to 2 communities