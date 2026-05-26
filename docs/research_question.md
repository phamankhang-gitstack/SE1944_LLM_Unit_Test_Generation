# Research Question

## Main RQ

Với các hàm Java/Python có độ phức tạp trung bình, GPT-4 tự sinh unit test có đạt branch coverage >= 80% và mutation score >= 60% không, khi so với unit test viết thủ công bởi sinh viên?

## Sub-questions

1. GPT-4 có đạt branch coverage trung bình >= 80% trên bộ hàm được chọn không?
2. GPT-4 có đạt mutation score trung bình >= 60% trên bộ hàm được chọn không?
3. Unit test do GPT-4 sinh tốt hơn, tương đương, hay kém hơn unit test do sinh viên viết thủ công?
4. Những loại hàm hoặc tình huống nào khiến GPT-4 sinh test kém hiệu quả?

## Metrics

- Branch coverage: measured by JaCoCo or equivalent tool.
- Mutation score: measured by PIT/PiTest or equivalent tool.
- Compile/pass status: whether generated tests compile and run successfully.
- Optional effort metric: time spent writing manual tests.

