---
type: community
cohesion: 0.10
members: 38
---

# test_image_vision.py

**Cohesion:** 0.10 - loosely connected
**Members:** 38 nodes

## Members
- [[A corpus with one raster image, one svg (text), and one markdown doc.]] - rationale - tests/test_image_vision.py
- [[Build `_ImageRef`s for raster images.      `read_bytes=True` (base64 backends) l]] - rationale - graphify/llm.py
- [[Build the Anthropic `messages.content` value (str, or block list with images).]] - rationale - graphify/llm.py
- [[Build the OpenAI-compatible user `content` value (str, or part list with images)]] - rationale - graphify/llm.py
- [[Return refs with pixel data dropped (for non-vision backends).]] - rationale - graphify/llm.py
- [[Split a chunk into (text-like units, raster-image files).      A ``FileSlice`` i]] - rationale - graphify/llm.py
- [[Tests for image-vision support across the direct extraction backends.  Covers th]] - rationale - tests/test_image_vision.py
- [[Whether `backend`'s configured model can see images.      Ollama is special-case]] - rationale - graphify/llm.py
- [[_anthropic_content()]] - code - graphify/llm.py
- [[_backend_supports_vision()]] - code - graphify/llm.py
- [[_build_image_refs()]] - code - graphify/llm.py
- [[_fake_anthropic()]] - code - tests/test_image_vision.py
- [[_fake_boto3()]] - code - tests/test_image_vision.py
- [[_fake_openai()]] - code - tests/test_image_vision.py
- [[_make_corpus()_2]] - code - tests/test_image_vision.py
- [[_openai_content()]] - code - graphify/llm.py
- [[_partition_semantic_files()]] - code - graphify/llm.py
- [[_strip_pixels()]] - code - graphify/llm.py
- [[test_anthropic_content_has_base64_block()]] - code - tests/test_image_vision.py
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
- [[test_openai_content_has_data_uri()]] - code - tests/test_image_vision.py
- [[test_partition_keeps_slices_as_text()]] - code - tests/test_file_slice.py
- [[test_partition_splits_raster_from_text()]] - code - tests/test_image_vision.py
- [[test_path_backend_skips_byte_read_and_size_cap()]] - code - tests/test_image_vision.py
- [[test_pdf_is_not_treated_as_vision_image()]] - code - tests/test_image_vision.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_image_visionpy
SORT file.name ASC
```

## Connections to other communities
- 17 edges to [[_COMMUNITY_llm.py]]
- 8 edges to [[_COMMUNITY_test_file_slice.py]]
- 8 edges to [[_COMMUNITY_test_llm_backends.py]]
- 4 edges to [[_COMMUNITY_test_chunking.py]]
- 2 edges to [[_COMMUNITY__call_llm]]
- 2 edges to [[_COMMUNITY__call_claude_cli]]

## Top bridge nodes
- [[_partition_semantic_files()]] - degree 8, connects to 4 communities
- [[test_image_vision.py]] - degree 30, connects to 3 communities
- [[_build_image_refs()]] - degree 19, connects to 3 communities
- [[_make_corpus()_2]] - degree 14, connects to 2 communities
- [[_anthropic_content()]] - degree 8, connects to 2 communities