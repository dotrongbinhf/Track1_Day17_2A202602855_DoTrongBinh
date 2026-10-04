# Track 1 · Day 17 — Đỗ Trọng Bình

> Bài chuẩn bị theo Case A — AI Tutor: Diagnostic Refresher. Các nhận định ở Chặng 1 là giả thuyết trước phỏng vấn. Đã bổ sung phân tích transcript P01, tách lời kể khỏi suy luận và ghi rõ những điểm chưa được kiểm chứng.

## 1. Thông tin cá nhân và nhóm

| Thông tin | Nội dung |
|---|---|
| Mã học viên | 2A202602855 |
| Họ và tên | Đỗ Trọng Bình |
| Tên nhóm | ThreeWhites |
| Số thành viên | 3 |
| Thành viên 1 | Đào Trọng Khang — MHV: 2A202602974 |
| Thành viên 2 | Nguyễn Tiến Phát — MHV: 2A202602387 |
| Thành viên 3 | Đỗ Trọng Bình — MHV: 2A202602855 |
| Case đã chọn | Case A — AI Tutor: Diagnostic Refresher |

## 2. Problem Hypothesis Brief — Chặng 1

> **Case đã xác nhận:** Case A — AI Tutor: Diagnostic Refresher, theo directive nhóm cung cấp. Directive là đầu vào của bài tập; các nhận định về hành vi, job, pain và outcome dưới đây vẫn là giả thuyết. Evidence Map ở 2.6 là kế hoạch trước phỏng vấn. Phân tích dữ liệu P01 nằm ở 2.9 và Interview Record; chưa dùng lời kể này để xác nhận giả thuyết A/B.

### 2.1 Solution: gỡ solution khỏi hình thức cụ thể

**Solution directive nguyên văn:**

> Thêm nút **“Tôi vẫn chưa hiểu”** vào bài học. Khi học viên bấm nút, AI Tutor sử dụng nội dung bài hiện tại, các câu trả lời gần đây và lịch sử học tập để: 1. Đặt 2–3 câu hỏi chẩn đoán ngắn. 2. Chọn một khái niệm nền để học viên ôn lại. 3. Tạo một phần giải thích ngắn. 4. Đưa học viên trở về bài đang học.

| Thành phần | Solution đã mô tả |
| :--- | :--- |
| Trigger | Học viên bấm “Tôi vẫn chưa hiểu” |
| Input | Bài hiện tại, câu trả lời gần đây và lịch sử học tập |
| AI action | Chẩn đoán và lựa chọn khái niệm nền |
| Output | Một phần ôn lại ngắn trước khi quay lại bài hiện tại |
| User control | Học viên chủ động yêu cầu trợ giúp |

- **Capability trung tính:** Giúp học viên làm rõ chỗ chưa hiểu, tiếp cận phần kiến thức liên quan cần làm rõ và tiếp tục hiểu hoặc thực hiện nội dung đang học.
- **Những yếu tố đã gỡ khỏi capability:** Nút bấm, tên AI Tutor, số câu hỏi chẩn đoán, công nghệ AI và định dạng phần ôn ngắn. Không mặc định ôn kiến thức nền là cách duy nhất để vượt qua chỗ chưa hiểu.

### 2.2 Change: chuỗi thay đổi được kỳ vọng

`Solution → Học viên nhận được hỗ trợ phù hợp với chỗ chưa hiểu → Học viên làm rõ phần kiến thức đang cản trở mình → Học viên quay lại và tự giải thích hoặc áp dụng nội dung bài hiện tại → Tiếp tục học với mức hiểu tốt hơn`

Các thay đổi được kỳ vọng:

1. **Biết khác:** Học viên nhận ra cụ thể điều mình chưa hiểu và mối liên hệ của nó với nội dung đang học, thay vì chỉ biết mình đang không theo kịp.
2. **Làm khác:** Học viên thực hiện bước làm rõ phù hợp, rồi quay lại thử giải thích hoặc làm bài bằng hiểu biết của mình.
3. **Kết quả khác:** Học viên có thể tiếp tục bài hiện tại và áp dụng được nội dung, với ít thời gian tìm kiếm không hiệu quả hơn.

**Output team tạo ra:** Các câu hỏi chẩn đoán và một phần ôn lại ngắn. **Outcome team có thể ảnh hưởng:** Học viên hiểu và tự thực hiện được bước tiếp theo. Việc bấm nút, đọc phần ôn hoặc quay lại màn hình bài học chưa chứng minh đã hiểu. Chuỗi có thể đứt nếu chẩn đoán sai, phần ôn không phù hợp hoặc học viên không áp dụng được khi quay lại.

### 2.3 Actor: các nhóm người liên quan

| Actor | Họ đang làm gì? | Pain hoặc hậu quả có thể có | Họ hưởng lợi thế nào? |
| :--- | :--- | :--- | :--- |
| Học viên | Học nội dung và tìm cách hiểu hoặc làm được phần đang học | Chưa biết vì sao không hiểu hoặc nên làm gì tiếp; có thể tìm kiếm kéo dài, bỏ qua phần đó hay dừng học | Làm rõ được chỗ vướng và tiếp tục học |
| Giảng viên/người hỗ trợ học tập | Trả lời câu hỏi và giúp học viên làm rõ nội dung | Khó hiểu chính xác học viên đang vướng ở đâu; có thể phải trao đổi nhiều lượt | Có thể hỗ trợ đúng chỗ hơn nếu hiểu rõ bối cảnh |
| Người biên soạn bài học | Thiết kế nội dung, ví dụ và trình tự học | Khó nhận ra đoạn giải thích chưa rõ hoặc yêu cầu kiến thức trước chưa phù hợp | Có căn cứ cải thiện bài học nếu các điểm vướng được kiểm chứng |

- **Actor nhóm chọn để điều tra trước:** Học viên đã có lúc không hiểu một phần bài học và tìm cách xử lý trong bảy ngày gần đây.
- **Vì sao chọn nhánh này:** Đây là người trực tiếp trải nghiệm tình huống, lựa chọn cách xử lý và chịu ảnh hưởng đến việc học. Lời kể của giảng viên không thay thế được trình tự hành động và kết quả thực tế của học viên.

### 2.4 Situation & Job

- **Tình huống bắt đầu khi:** Trong lúc đọc, xem hoặc thực hành một bài học, học viên nhận ra mình chưa hiểu một phần nội dung để tiếp tục việc đang làm. Không lấy hành động bấm nút làm situation vì job tồn tại cả khi không có nút.
- **Actor đang cố hoàn thành việc gì:** Hiểu phần nội dung đó đủ để tự giải thích, thực hiện bước tiếp theo hoặc làm bài liên quan.
- **Hiện tại họ làm việc đó như thế nào — giả thuyết:** Đọc/xem lại, thử làm lại, tìm tài liệu hoặc hỏi người khác. Đây là các cách dự kiến trước phỏng vấn. P01 đã tự báo cáo một số cách xử lý; xem 2.9 để biết mức độ evidence và giới hạn.
- **Điểm bắt đầu gặp vướng mắc — giả thuyết A:** Học viên chưa nắm vững một phần kiến thức liên quan đã học trước, nhưng không xác định được phần nào cần làm rõ để hiểu bài hiện tại.
- **Mô tả Situation & Job:** Khi đang học và nhận ra mình chưa hiểu một phần nội dung, học viên đang cố hiểu và áp dụng phần đó bằng những cách xử lý họ tự lựa chọn, trước khi tiếp tục bài học.
- **JTBD hypothesis:** Khi gặp một phần bài học mình chưa hiểu, tôi muốn làm rõ phần đó và biết mình đã hiểu đến đâu, để có thể tự thực hiện bước tiếp theo của bài đang học.

### 2.5 Pain: các cách giải thích cạnh tranh

**Hiện tượng chung cần kiểm tra:** Học viên gặp một phần bài chưa hiểu và việc tự xử lý có thể mất công hoặc chưa giúp họ tiếp tục học. Không mặc định mọi lần chưa hiểu đều là pain đáng giải.

- **Pain Hypothesis A — kiến thức nền chưa vững và khó xác định chỗ cần làm rõ:** Khi không hiểu một phần bài học, học viên khó tự làm rõ nội dung để tiếp tục vì chưa nắm vững kiến thức liên quan đã học trước và không biết phần nào đang cản mình, dẫn đến đọc/xem lại hoặc tìm kiếm nhiều lần nhưng vẫn không tự làm được bước tiếp theo.
- **Pain Hypothesis B — cách giải thích của bài hiện tại chưa rõ:** Khi không hiểu một phần bài học, học viên khó tiếp tục dù đã nắm được kiến thức liên quan trước đó vì cách diễn đạt, ví dụ hoặc bước chuyển trong bài hiện tại chưa giúp họ hiểu cách áp dụng, dẫn đến phải tìm cách giải thích khác hoặc nhờ người giải thích lại.
- **Giả thuyết chọn để điều tra trước:** A.
- **Lý do chọn:** Directive đặt cược vào việc chẩn đoán và ôn một khái niệm nền. Cần kiểm tra giả định này trước khi chọn hướng triển khai; chọn A để thử một giả định rủi ro, không vì A đã được chứng minh.
- **Cách phân biệt A và B:** Dựng lại chính xác phần chưa hiểu, những việc học viên đã làm và điều giúp họ tiếp tục. Việc làm rõ một khái niệm đã học trước rồi áp dụng được ở bài hiện tại có thể ủng hộ A. Nếu họ đã thể hiện hiểu phần đó và chỉ cần một ví dụ/cách diễn đạt khác của bài hiện tại, cần xem lại A và cân nhắc B. Không kết luận nguyên nhân chỉ vì họ nói “tôi thiếu nền” hoặc đã mở một bài cũ; cần hành động và kết quả cụ thể. Hai barrier có thể cùng tồn tại.

### 2.6 Evidence Map

| Cần kiểm tra | Evidence làm nhóm tin hơn vào A | Evidence làm nhóm nghi ngờ hoặc bác bỏ A |
| :--- | :--- | :--- |
| Situation có thật | Kể được sự kiện trong bảy ngày gần đây: bài đang học, phần chưa hiểu, việc muốn làm và thời điểm nhận ra | Không có sự kiện phù hợp; chỉ nói chung về thói quen hoặc tưởng tượng. Người đó chưa đáp ứng tiêu chí nghiên cứu lần này |
| Pain có ý nghĩa | Kể được chuỗi đọc/xem lại, thử làm hoặc tìm kiếm nhưng chưa tiếp tục được; nêu công sức và điểm vẫn chưa rõ | Chỉ cần xử lý rất ngắn bằng cách hiện có và tiếp tục dễ dàng; hoặc có thể làm rõ vấn đề ngay mà không ảnh hưởng việc học |
| Workaround tồn tại | Có hành động tìm lại nội dung liên quan, hỏi để xác định chỗ vướng hoặc thử nhiều nguồn; kể được cách chọn và kết quả từng cách | Hiểu kiến thức liên quan trước đó và giải quyết được bằng cách diễn đạt khác của bài hiện tại, nghiêng về B. Không có workaround tự nó chưa đủ bác bỏ pain |
| Consequence tồn tại | Có sự kiện phải bỏ dở, bỏ qua đoạn học hoặc chưa tự làm được bài sau khi tìm cách xử lý; đối chiếu trình tự và kết quả nếu có | Tiếp tục học bình thường, không có ảnh hưởng đáng kể; hoặc ngừng học vì một lý do khác. Dừng học đơn lẻ không chứng minh do kiến thức nền |
| Pattern có lặp | Có lần trước với diễn biến tương tự; kể được nội dung, hành động và kết quả để đối chiếu | Chỉ xảy ra với một đoạn diễn đạt đặc biệt khó hiểu; các lần khác xử lý thuận lợi. Cần thu hẹp phạm vi hoặc chuyển sang B |

**Problem Hypothesis nhóm mang sang Chặng 2:**

> Khi gặp một phần bài học chưa hiểu, học viên khó tự làm rõ để tiếp tục vì chưa nắm vững kiến thức liên quan đã học trước và không xác định được phần nào đang cản mình. Họ có thể đọc/xem lại hoặc tìm kiếm nhiều lần nhưng vẫn chưa tự thực hiện được bước tiếp theo, làm gián đoạn việc học.

**Điều gì phải đúng để giả thuyết đứng vững:**

1. Học viên thực sự muốn hiểu hoặc áp dụng nội dung và đã có hành động tìm cách xử lý.
2. Có kiến thức liên quan chưa vững đang cản việc hiểu bài hiện tại; không chỉ suy ra từ cảm giác chưa hiểu.
3. Việc xác định và làm rõ chỗ vướng hiện tại gây công sức hoặc gián đoạn đáng kể.
4. Sau khi làm rõ phần liên quan, học viên có thể quay lại và thể hiện hiểu/áp dụng tốt hơn. Đây là mối liên hệ cần kiểm tra, chưa được chứng minh.

**Điều gì có thể khiến nhóm sửa hoặc bác bỏ giả thuyết:**

- Học viên đã nắm và dùng được kiến thức liên quan; trở ngại nằm ở cách giải thích hoặc ví dụ của bài hiện tại, nghiêng về B.
- Các cách xử lý hiện có đã giúp học viên tiếp tục nhanh và hiệu quả; pain không đủ đáng kể trong nhóm được nghiên cứu.
- Học viên đã ôn phần liên quan nhưng vẫn không hiểu hoặc không áp dụng được; cần xem lại chẩn đoán nguyên nhân.
- Việc học bị ngắt bởi yếu tố khác, không phải chỗ chưa hiểu; hoặc tình huống hiếm, cần thu hẹp phạm vi.

### 2.7 Solution Parking Lot

Chỉ xem xét các hướng sau khi có evidence; không đưa danh sách này cho người được phỏng vấn.

| Hướng giải quyết có thể có | AI / Không sử dụng AI |
| :--- | :--- |
| 1. Liên kết do người biên soạn chọn tới phần kiến thức liên quan, có chỉ dẫn quay lại bài đang học | Không sử dụng AI |
| 2. Câu tự kiểm tra và gợi ý theo đáp án được soạn sẵn, giúp học viên xác định phần cần làm rõ | Không sử dụng AI |
| 3. Bổ sung ví dụ từng bước và cách diễn đạt khác cho đoạn bài thường gây vướng; phù hợp nếu B được ủng hộ | Không sử dụng AI |
| 4. Trao đổi ngắn với giảng viên/bạn học, dùng bài làm hoặc đoạn chưa hiểu để làm rõ chỗ vướng | Không sử dụng AI |
| 5. Sơ đồ khái niệm và bảng thuật ngữ liên quan để học viên tự định hướng khi cần | Không sử dụng AI |
| 6. Hỗ trợ chẩn đoán bằng AI, chọn phần ôn phù hợp rồi kiểm tra khả năng quay lại áp dụng ở bài hiện tại | AI |

### 2.8 Tóm tắt CHECKPOINT 1 — Problem Hypothesis

- **Chuỗi lập luận:** Khả năng làm rõ chỗ chưa hiểu → học viên thực hiện bước làm rõ và quay lại áp dụng → actor là học viên → situation là gặp phần bài chưa hiểu → A: kiến thức liên quan chưa vững và khó xác định chỗ vướng → tìm câu chuyện, hành động, cách xử lý và kết quả thực tế.
- **Giải thích cạnh tranh:** B cho rằng cách giải thích của bài hiện tại là barrier chính dù kiến thức liên quan trước đó đã đủ.
- **Dấu hiệu có thể làm A sai:** Học viên thể hiện đã hiểu kiến thức liên quan và tiếp tục được nhờ một cách diễn đạt/ví dụ khác, hoặc cách xử lý hiện tại đã hiệu quả với ít công sức.
- **Trạng thái:** Đã soạn CP1 theo Case A và phân tích một transcript P01. Chưa đủ evidence để xác nhận hoặc bác bỏ A/B; có thêm tín hiệu về thời gian xử lý trong lớp cần điều tra.

### 2.9 Cập nhật sau phỏng vấn P01 — không thay thế giả thuyết ban đầu

Nguồn phân tích: [Interview Record](interview/notes.md) và [transcript nguyên văn](interview/transcript.md). Đã có [bản ghi M4A](interview/recording.m4a), dài 05:29,6 theo metadata; chưa kiểm nghe từng câu để đối chiếu transcript. P01 là mã nội bộ được gán khi tổng hợp. Lời kể chủ yếu mô tả thói quen/điều kiện; chưa dựng được một lần cụ thể với bài học, thời gian, hành động và kết quả.

| Thành phần Evidence Map | Dữ liệu đã có | Điều có thể kết luận / còn thiếu |
| :--- | :--- | :--- |
| Situation | P01 nói trong bảy ngày qua có phần kiến thức không hiểu khi học trên lớp | Phù hợp sơ bộ theo tự báo cáo; chưa có ngày, bài và đoạn cụ thể |
| Pain có ý nghĩa | Tự báo cáo khó dành thời gian tra cứu khi bài giảng tiếp tục, ghi lại để xem sau; bài tập mang về có thể hạn chế thời gian tìm hiểu sâu | Có tín hiệu về thời gian, chưa có công sức đo được hoặc mức ảnh hưởng trong một sự kiện |
| Workaround | Tự nhắc ChatGPT/Claude, ghi lại; kể việc hỏi bạn trong phần sau | Biết các cách họ mô tả, chưa biết hiệu quả từng cách. Phần kể hỏi bạn xuất hiện sau câu hỏi gợi ý, cần đào sâu lại |
| Consequence | P01 nói có thể không có thời gian tìm hiểu sâu | Chưa xác nhận trễ bài, bỏ dở hoặc không hiểu phần tiếp theo. Không biến các hậu quả interviewer gợi ý thành fact |
| Theo hành vi người tham gia tự kể | Nếu họ kể đã ghi lại: “Sau khi ghi lại, chuyện gì xảy ra với phần đó?”; nếu họ kể đã tra cứu: “Lúc đó bạn đã hỏi gì?”, “Bạn nhận được câu trả lời thế nào?”, “Sau đó bạn làm gì?” — hỏi từng câu, không mặc định kết quả |
| Pattern | P01 nói “ngày nào mình cũng gặp” | Tần suất tự báo cáo, chưa có hai sự kiện cụ thể để đối chiếu; không suy rộng sang học viên khác |

**A/B sau lượt này:** Chưa xác nhận A (kiến thức nền chưa vững) hoặc B (cách giải thích của bài hiện tại chưa rõ). Transcript không có khái niệm, ví dụ bài làm hoặc kết quả đủ để phân biệt. Việc thiếu thời gian có thể cùng tồn tại với A/B, không tự bác bỏ chúng.

**Giả thuyết bổ sung H3 — cần điều tra, không đổi case:** Khi học trên lớp và gặp phần chưa hiểu trong lúc bài giảng tiếp tục, học viên có thể khó dành thời gian tự làm rõ hoặc tiếp cận hỗ trợ đúng lúc, nên ghi lại để xem sau; việc tìm hiểu có thể bị trì hoãn khi ngoài lớp còn bài tập. H3 hiện dựa vào lời kể chung của P01, chưa phải nguyên nhân đã được chứng minh.

**Không dùng làm bằng chứng xác nhận solution:** Câu trả lời muốn công cụ trả lời ngay xuất hiện sau khi interviewer giới thiệu hướng đó. Mong muốn đáp án chính xác/cá nhân hóa là nguyện vọng, chưa chứng minh pain, khả năng tiếp tục học hoặc nhu cầu dùng Diagnostic Refresher.

**Điều cần tìm tiếp:** Một buổi học cụ thể, phần chưa hiểu, từng cách xử lý và kết quả ngay sau mỗi bước; có quay lại phần đã ghi hay không; lần cách hiện có xử lý thuận lợi; dấu hiệu để phân biệt thiếu thời gian, kiến thức liên quan và cách giải thích. Không chọn solution mới chỉ từ lượt này.

## 3. Conversation Guide phiên bản cuối

> Mục 3.1 lưu Big 3 dự kiến trước phỏng vấn. Mục 3.2 ghi đúng kịch bản đã sử dụng trong P01; mục 3.5 là Conversation Guide phiên bản cuối đã sửa sau luyện, chưa dùng trong một lượt mới. Các câu gợi ý công cụ trong buổi thực tế được giữ lại và đánh giá, không sửa lịch sử phỏng vấn.

### 3.1 Big 3: ba điều quan trọng nhất cần học

| Điều cần học | Evidence cần tìm | Điều gì khiến nhóm xem lại giả thuyết? |
| :--- | :--- | :--- |
| **1. Học viên chưa hiểu phần nào và đang muốn hiểu/làm được điều gì trong sự kiện gần nhất?** Kiểm tra situation và job, tìm bối cảnh để phân biệt A/B | Bài và phần cụ thể; thời điểm nhận ra; việc đang làm; điều họ đã thử và chỗ chưa làm được. Nếu họ tự đề cập kiến thức liên quan, tìm ví dụ cụ thể về điều đã hiểu/chưa hiểu | Không có sự kiện phù hợp; job khác giả định; hoặc họ đã hiểu phần liên quan trước đó và vướng ở cách diễn đạt của bài hiện tại |
| **2. Học viên đã xử lý ra sao, bỏ ra công sức gì và kết quả sau từng bước/cuối lần đó thế nào?** Gộp hành vi, workaround và kết quả trong cùng một mạch kể | Trình tự đọc/xem lại, thử làm, tìm kiếm hoặc trao đổi do họ tự kể; lý do chọn từng cách; thời gian/công sức; kết quả mỗi bước và việc học sau lần xử lý đó. Không đưa sẵn các lựa chọn cách xử lý | Họ đã biết chính xác cần làm gì và cách hiện có giải quyết dễ dàng; hoặc cách hữu ích không liên quan đến ôn kiến thức nền |
| **3. Câu hỏi “đáng sợ”: Việc chưa hiểu có thực sự gây ảnh hưởng đáng kể, hay cách xử lý hiện có đã đủ tốt và nhóm đang chọn sai vấn đề?** Kiểm tra consequence và tính lặp lại | Sau khi xử lý, họ tiếp tục thế nào; có tự giải thích/làm được phần liên quan không; việc chưa hoàn tất nếu có; một sự kiện trước để đối chiếu. Không lấy việc nói “đã hiểu” làm bằng chứng duy nhất | Tiếp tục học nhanh, ít công sức và không có ảnh hưởng đáng kể; chỉ một sự cố hiếm; hoặc ôn phần liên quan không giúp còn cách giải thích khác giúp, cần xem lại A |

### 3.2 Kịch bản đã sử dụng trong buổi P01

Nguồn: [kịch bản thực tế](interview/guide-used.md), trích nguyên văn sáu lượt interviewer từ [transcript](interview/transcript.md). Bản ghi đã có tại [recording.m4a](interview/recording.m4a), dài **05:29,6** theo metadata. Bảng dưới tóm tắt trình tự, kèm trích đoạn nguyên văn; không viết lại câu đã hỏi thành phiên bản trung tính.

| Thứ tự | Nội dung đã hỏi/nói theo transcript | Ghi nhận |
| :--- | :--- | :--- |
| 1. Mở đầu và xin phép ghi âm | Nêu mục đích tìm hiểu trải nghiệm chưa hiểu bài, cho phép bỏ qua; hỏi “bạn có đồng ý là cho phép mình ghi âm không?” | P01 trả lời “Ừm, đồng ý.”. Lời mở đầu đầy đủ được giữ trong guide-used.md |
| 2. Story opener | “bạn có thể kể cho mình nghe về cái lần gần nhất trong vòng 7 ngày qua bạn không hiểu một phần bài học nào và bạn đã tìm cái cách xử lý như thế nào nhé?” | P01 chuyển sang mô tả thói quen/điều kiện; chưa neo lại một sự kiện riêng |
| 3. Hỏi mục tiêu rồi gợi ý hậu quả | “mình muốn hiểu cái gì và mình muốn làm được cái gì.”, sau đó hỏi “bạn đã bạn sẽ muốn là mình có thể hiểu được ngay cái phần đấy không?” | Interviewer đưa trước khả năng không hiểu phần tiếp theo; không phải câu hỏi trung tính chỉ về hành vi quá khứ |
| 4. Gợi ý công cụ trả lời ngay | “bạn có muốn là có được một cái công cụ như vậy không?” | Hỏi mong muốn về hướng công cụ được interviewer giới thiệu; không coi lời đồng ý là bằng chứng xác nhận solution |
| 5. Mời bổ sung | “bạn muốn mình có thể là hỏi thêm không?” | P01 đề nghị cá nhân hóa và nhận xét về người khác; chưa phải evidence cho những người đó |
| 6. Kết thúc | Cảm ơn và chúc người tham gia một ngày tốt đẹp | Kết thúc lượt phỏng vấn |

**So với Big 3 dự kiến:** Có lời kể về situation và cách xử lý chung; chưa dựng hành động–kết quả trong một lần, chưa hỏi công sức cụ thể hoặc đối chiếu sự kiện trước. Không ghi rằng buổi đã hỏi đủ ba câu của guide ban đầu. Câu hỏi trung tính để bổ sung evidence nằm ở 3.5.

### 3.3 Tự rà soát và phân công

- **Người phỏng vấn lượt đã ghi nhận:** Đỗ Trọng Bình, theo thông tin bài tập; transcript dùng nhãn “Người phỏng vấn”.
- **Người đã được phỏng vấn:** P01 — đáp ứng tiêu chí tuyển theo tự báo cáo về bảy ngày gần đây. Chưa xác nhận người này ngoài nhóm và chưa dựng một sự kiện riêng để phân tích pain.
- **Người ghi chú:** Đỗ Trọng Bình; có thể phân công một thành viên ghi chú nếu nhóm bố trí được.
- **Nơi ghi Interview Record:** [interview/notes.md](interview/notes.md).
- **Phân công nhóm:** Đã có danh sách thành viên ở mục 1, nhưng chưa có danh sách cặp “interviewer → người được phỏng vấn” của cả nhóm. Mỗi thành viên cần chốt người đáp ứng tiêu chí.
- **Chỉnh guide sau khi xem transcript P01:** Thêm câu neo lại một buổi học khi lời kể chung chung; lượt tiếp theo hỏi từng hành động và kết quả; bỏ câu hỏi giới thiệu công cụ hoặc hỏi mong muốn tương lai. Đây là điều chỉnh sau lượt đã có, không khẳng định đã thực hiện một lượt luyện/đổi vai riêng.

**Tự rà soát guide đề xuất ở 3.5 — không áp dụng các dấu hoàn thành này cho kịch bản đã dùng ở 3.2:**

- [x] Lời mở đầu và các câu hỏi không làm lộ solution.
- [x] Không gợi ý rằng nguyên nhân là thiếu kiến thức nền, bài giải thích chưa rõ hoặc một công cụ cụ thể.
- [x] Không hỏi ý kiến về tính năng hoặc dự đoán tương lai.
- [x] Story opener neo vào “lần gần nhất” trong bảy ngày qua.
- [x] Đúng ba câu hỏi chính, nối trực tiếp với Big 3.
- [x] Có câu hỏi có thể làm giả thuyết yếu đi: kết quả trong mạch kể và việc đối chiếu sự kiện trước có thể cho thấy cách xử lý hiện tại đã đủ tốt hoặc tình huống không lặp lại.
- [x] Probes đào hành vi–workaround–hậu quả và đối chiếu sự kiện trước, theo lời kể thực tế.
- [x] P01 tự báo cáo trải nghiệm phù hợp tiêu chí tuyển bảy ngày; vẫn cần sự kiện cụ thể làm evidence chính.
- [ ] Mỗi thành viên đã biết mình phỏng vấn ai — cần chốt cặp cụ thể.

### 3.4 CHECKPOINT 2 — Interview-ready

**Guide bổ sung ở 3.5 đã được soạn và rà soát theo Case A:** bắt đầu từ sự kiện gần đây, ba câu chính nối với Big 3 và probes đào hành động–kết quả. Kịch bản thực tế ở 3.2 chưa đáp ứng đủ các tiêu chí này, do chưa neo sự kiện và có câu hỏi gợi ý công cụ.

**Cập nhật sau P01:** Đã có transcript và recording.m4a (05:29,6), nhưng việc thực hiện lệch guide ở phần câu hỏi gợi ý công cụ và chưa neo được sự kiện cụ thể. Lượt bổ sung cần kiểm tra lại bối cảnh, đào hành động–kết quả và tìm bằng chứng ngược. Chưa có dữ liệu xác nhận phân công đầy đủ cho nhóm hoặc lượt đổi vai.

### 3.5 Conversation Guide phiên bản cuối — đã sửa sau P01

> Các câu dưới đây là phiên bản đã sửa sau khi xem transcript P01; chưa dùng để thực hiện một lượt mới. Không ghi nhận chúng là câu đã hỏi trong buổi đã diễn ra; kịch bản thực tế nằm ở 3.2 và interview/guide-used.md.

**Tiêu chí tuyển người:** Chúng tôi cần nói chuyện với học viên đã có lúc không hiểu một phần bài học và phải tìm cách xử lý trong **bảy ngày gần đây**. Không yêu cầu họ từng dùng một sản phẩm cụ thể, từng ôn kiến thức nền hoặc từng thất bại khi tìm cách xử lý. Tuyển cả người đã giải quyết được để kiểm tra bằng chứng ngược.

**Recruitment check — dùng để tuyển đúng người, không tính là evidence chính:**

> Trong bảy ngày gần đây, bạn có lần nào không hiểu một phần bài học và đã tìm cách xử lý không?

Nếu không có sự kiện phù hợp, tìm người khác, không yêu cầu tưởng tượng. Sau khi tuyển vẫn phải dựng lại sự kiện trong phỏng vấn.

**Lời mở đầu:**

> Chào bạn, cảm ơn bạn đã dành thời gian trò chuyện với mình. Mình đang làm một bài tập tìm hiểu trải nghiệm học tập, cụ thể là những lúc người học gặp một phần bài chưa hiểu và tìm cách xử lý.
>
> Mình muốn nghe một lần cụ thể bạn đã trải qua gần đây: lúc đó bạn đang học gì, bạn muốn làm được điều gì, bạn đã làm gì và cuối cùng mọi việc diễn ra thế nào. Không có câu trả lời đúng hay sai, bạn cứ kể theo trải nghiệm của mình, kể cả khi bạn đã xử lý được và việc học diễn ra thuận lợi. Nếu có câu nào không muốn trả lời thì bạn có thể bỏ qua.
>
> Mình xin phép ghi âm cuộc trò chuyện để xem lại và ghi chép cho bài tập, không chia sẻ công khai. Bạn có đồng ý cho mình ghi âm không? Nếu không tiện thì mình chỉ ghi chú thôi.

**Trước khi bắt đầu:** Chờ người tham gia trả lời rõ ràng. Chỉ bật ghi âm sau khi họ đồng ý; nếu không đồng ý, tiếp tục bằng ghi chú. Ghi đúng trạng thái đồng ý trong Interview Record.

**Story opener:**

> Kể mình nghe về lần gần nhất trong bảy ngày qua bạn không hiểu một phần bài học và đã tìm cách xử lý?

Để người tham gia kể trước. Khi cần, làm rõ bằng “Lần đó diễn ra khi nào?” hoặc “Bạn đang học phần nào?”. Nếu họ trả lời bằng thói quen như “thường”, “ngày nào”, neo lại: “Bạn chọn một buổi học gần đây mà bạn nhớ rõ nhất nhé. Buổi đó là khi nào?”. Nếu câu chuyện đã trả lời một câu chính, chỉ hỏi sâu phần còn thiếu.

**Big 3 Questions — chỉ đọc cột câu hỏi:**

| Điều cần học — ghi chú nội bộ | Câu hỏi sẽ dùng |
| :--- | :--- |
| **1. Phần chưa hiểu và việc muốn hoàn thành** | **“Lúc đó, bạn đang cố hiểu hoặc làm được điều gì?”** |
| **2. Hành động và kết quả thực tế — cùng một mạch kể** | **“Từ lúc nhận ra mình chưa hiểu, bạn đã xử lý thế nào và cuối cùng lần đó ra sao?”** |
| **3. Đối chiếu sự kiện trước để kiểm tra mức độ và tính lặp lại** | **“So với lần gần nhất trước đó bạn gặp chuyện tương tự, lần này có gì giống và khác?”** |

**Mạch hỏi hành động và kết quả:** Để người tham gia kể từng việc đã làm, rồi hỏi kết quả ngay sau bước đó khi chưa rõ: “Sau khi làm việc đó thì chuyện gì xảy ra?”. Tiếp tục theo câu chuyện bằng “Rồi bạn làm gì tiếp?”. Cuối mạch, nếu chưa rõ kết quả chung, hỏi “Sau đó việc học của bạn diễn ra thế nào?”. Nếu họ nói đã hiểu, có thể hỏi “Sau đó bạn đã làm được gì với phần vừa học?”. Không tách thành hai lượt bắt họ kể lại hành động rồi kể lại kết quả.

Câu 3 giúp đối chiếu hai sự kiện, kể cả trường hợp cách xử lý hiện có đã hiệu quả và không có pain đáng kể. Nếu họ không nhớ hoặc chưa có lần trước, ghi nhận và bỏ qua; không yêu cầu tưởng tượng. Không mặc định họ bỏ dở, mất nhiều thời gian hoặc vẫn chưa hiểu.

**Probe bank — chỉ dùng khi câu chuyện cần đào sâu, hỏi từng câu:**

| Khi cần làm rõ | Câu hỏi trung tính |
| :--- | :--- |
| Bối cảnh và dấu hiệu | “Lúc đó bạn đang làm gì?”; “Bạn nhận ra mình chưa hiểu như thế nào?” |
| Phần cụ thể | “Bạn kể rõ hơn về đoạn bạn vừa nhắc được không?” |
| Hành vi | “Lúc đó chuyện gì xảy ra tiếp theo?”; “Bạn đã làm gì?” |
| Căn cứ chọn cách xử lý | “Vì sao lúc đó bạn chọn cách đó?” |
| Thời gian/công sức | “Việc đó diễn ra trong khoảng bao lâu?” — chấp nhận không nhớ, không ép một con số |
| Cách xử lý khác — chỉ sau khi đã kể một cách | “Trước cách đó, bạn đã thử cách nào khác chưa?” |
| Chỗ vướng — chỉ sau khi họ tự mô tả | “Bạn vừa nói ‘[đúng từ người tham gia dùng]’; lúc đó cụ thể chuyện gì xảy ra?” |
| Kết quả từng bước | “Sau khi làm việc đó, bạn đã làm gì tiếp?”; “Bạn dựa vào điều gì để biết kết quả đó?” |
| Khả năng tiếp tục | “Khi quay lại việc đang làm, bạn đã làm như thế nào?” — chỉ dùng nếu họ đã kể có quay lại |
| Theo hành vi người tham gia tự kể | Nếu họ kể đã ghi lại: “Sau khi ghi lại, chuyện gì xảy ra với phần đó?”; nếu họ kể đã tra cứu: “Lúc đó bạn đã hỏi gì?”, “Bạn nhận được câu trả lời thế nào?”, “Sau đó bạn làm gì?” — hỏi từng câu, không mặc định kết quả |
| Pattern | “Lần gần nhất trước đó bạn gặp chuyện tương tự là khi nào?”; “Trong lần đó, bạn đã làm gì?” |

Dùng đúng từ người tham gia nói, không tự đổi “chưa hiểu” thành “thiếu nền”. Không nêu tên khái niệm, nguyên nhân hay cách xử lý mà họ chưa nhắc. Không hỏi họ có muốn một công cụ mới hoặc sẽ dùng một tính năng không. Nếu họ đã xử lý thuận lợi, đào cách làm và kết quả đó thay vì ép câu chuyện về khó khăn.

**Ba phản xạ khi data bắt đầu lệch:**

| User đưa ra | Phản xạ | Cách quay lại evidence |
| :--- | :--- | :--- |
| Lời khen | **Deflect** | “Cảm ơn bạn. Quay lại lần bạn vừa kể, lúc đó bạn đã làm gì tiếp theo?” |
| Câu chung chung hoặc lời hứa tương lai | **Anchor** | “Lần gần nhất chuyện đó xảy ra là khi nào?” Sau đó dựng lại hành động trong lần cụ thể |
| Ý tưởng hoặc feature request | **Dig** | “Lần gần nhất bạn cần làm việc đó, bạn đã xử lý như thế nào?” Tìm job và cách làm đã xảy ra, không mời đánh giá ý tưởng |

**Kết thúc:** “Có chi tiết nào trong lần đó mình chưa hỏi tới không?” Sau khi nghe xong: “Cảm ơn bạn, vậy là mình hình dung rõ hơn rồi.”

**Cách sử dụng:** Hỏi từng câu, để người tham gia kể xong rồi mới hỏi tiếp. Probes là câu dự phòng, không cần hỏi hết; bỏ qua câu đã được trả lời trong câu chuyện. Không giới thiệu Case A, nút bấm, quy trình chẩn đoán, phần ôn hay các giả thuyết A/B cho người tham gia. Không đưa ví dụ câu trả lời hoặc lựa chọn nguyên nhân. Chỉ phân tích nguyên nhân sau khi ghi nhận câu chuyện, tách điều người tham gia nói/làm khỏi suy luận của nhóm.

## 4. Practice Reflection — Chặng 4

> Bản reflection dưới đây được soạn từ transcript P01 để người học rà soát trước khi nộp. Guide đã được sửa trong tài liệu; chưa có thông tin xác nhận nhóm đã chia sẻ và thống nhất bản chung.

### 4.1 Câu hỏi nào đã giúp user kể một tình huống cụ thể?

Câu mở đầu mình đã dùng là: “bạn có thể kể cho mình nghe về cái lần gần nhất trong vòng 7 ngày qua bạn không hiểu một phần bài học nào và bạn đã tìm cái cách xử lý như thế nào nhé?”. Câu này giúp người tham gia nhắc đến bối cảnh học trên lớp và các cách họ thường xử lý như tra cứu hoặc ghi lại. Tuy nhiên, mình **chưa mở được một tình huống cụ thể**: họ trả lời theo thói quen, còn mình chưa hỏi tiếp để chọn một buổi học, bài và phần chưa hiểu rõ ràng. Vì vậy, mình không coi câu này đã đạt mục tiêu chỉ vì có nhắc “lần gần nhất”. Lần tới, khi nghe “thường” hoặc “nếu”, mình sẽ hỏi: “Bạn chọn một buổi học gần đây mà bạn nhớ rõ nhất nhé. Buổi đó là khi nào và bạn đang học phần nào?”.

### 4.2 Chỗ nào mình cần làm tốt hơn ở lần phỏng vấn thật?

Mình cần dừng việc diễn giải thay người tham gia và follow hành vi họ vừa kể. Trong lượt P01, mình đưa trước khả năng không hiểu phần tiếp theo, rồi hỏi có muốn hiểu ngay không. Sau đó mình giới thiệu công cụ trả lời ngay và hỏi “bạn có muốn là có được một cái công cụ như vậy không?”. Những câu này dẫn dắt sang mong muốn tương lai, thay vì tìm việc đã xảy ra; lời đồng ý không chứng minh pain hoặc nhu cầu dùng solution.

Mình cũng bỏ lỡ tín hiệu “ghi lại để xem sau”: chưa hỏi họ ghi phần nào, sau đó đã làm gì và kết quả ra sao. Lần tới mình sẽ neo một sự kiện rồi hỏi từng hành động cùng kết quả ngay sau bước đó. Nếu họ kể ghi lại, mình hỏi “Sau khi ghi lại, chuyện gì xảy ra với phần đó?”; nếu họ kể tra cứu, mình hỏi họ đã hỏi gì, nhận được gì và làm gì tiếp. Mình cũng sẽ tìm lần cách xử lý hiện có đã hiệu quả để kiểm tra khả năng pain không đáng kể.

### 4.3 Sau khi luyện, nhóm đã sửa Conversation Guide ở đâu và vì sao?

Trong bản tài liệu cá nhân, guide cuối ở **3.5** đã được sửa dựa trên lượt P01. Chưa có thông tin xác nhận nhóm đã thống nhất những sửa đổi này thành guide chung; phần đó cần được người học cập nhật sau khi trao đổi với nhóm.

| Chỗ sửa sau lượt P01 | Nội dung trong guide cuối | Vì sao sửa |
| :--- | :--- | :--- |
| Lời kể dừng ở thói quen | Thêm câu chọn một buổi học, làm rõ thời điểm và phần đang học khi người tham gia kể chung chung | Câu mở đầu có “lần gần nhất” vẫn chưa đủ để có sự kiện cụ thể |
| Gợi ý hậu quả và công cụ mới | Bỏ câu hỏi muốn hiểu ngay/muốn công cụ; hỏi “Lúc đó, bạn đang cố hiểu hoặc làm được điều gì?” | Để người tham gia tự kể mục tiêu, không đưa hướng giải quyết hoặc hậu quả trước |
| Chưa đào hành động và kết quả | Gộp vào câu “Từ lúc nhận ra mình chưa hiểu, bạn đã xử lý thế nào và cuối cùng lần đó ra sao?”, rồi hỏi kết quả sau từng bước | Biết hiệu quả cách xử lý thực tế, tránh tách hai mạch khiến họ kể lại |
| Bỏ lỡ việc ghi lại/tra cứu | Thêm probes chỉ dùng khi người tham gia tự nhắc những hành vi đó | Đào sâu tín hiệu trong câu chuyện, không cung cấp sẵn cách xử lý |
| Chưa tìm bằng chứng ngược | Đối chiếu lần trước, kể cả lần đã xử lý thuận lợi | Kiểm tra tính lặp lại và khả năng cách hiện có đã đủ tốt |

**Nội dung để chia sẻ với nhóm:** Câu mở đầu trên có ích để bắt đầu lời kể nhưng chưa mở được sự kiện riêng; chỗ cần sửa rõ nhất là câu hỏi muốn công cụ. Cần trao đổi để nhóm thống nhất câu neo sự kiện và mạch hành động–kết quả trước fieldwork. Chưa ghi nhận việc chia sẻ này đã hoàn tất.

### 4.4 Hồ sơ thực hành CP3

#### 4.4.1 Hồ sơ lượt làm interviewer

- **Người phỏng vấn:** Đỗ Trọng Bình, theo thông tin bài tập.
- **Mã người tham gia:** P01.
- **Đúng tiêu chí tuyển:** **Có — theo tự báo cáo.** P01 nói trong bảy ngày qua có phần bài chưa hiểu và đã tìm cách xử lý. Recruitment không phải evidence chính về pain; buổi hỏi chưa dựng một sự kiện cụ thể.
- **Đã có lượt interviewer:** Có; transcript thể hiện lượt hỏi–đáp.
- **Ngày phỏng vấn:** Chưa được cung cấp.
- **Interview Record:** [interview/notes.md](interview/notes.md) — đã có bảng đúng năm mục của mẫu CP3, ghi chép chi tiết và giới hạn evidence.
- **Bản ghi:** [interview/recording.m4a](interview/recording.m4a) — đã có.
- **Thời lượng bản ghi:** **05:29,6** (329,6 giây), theo metadata M4A. Bản ghi ngắn hơn mốc 15 phút/lượt của đề; cần xác nhận đây là toàn bộ lượt hay một đoạn trích.
- **Transcript:** [interview/transcript.md](interview/transcript.md), giữ nguyên lời do người dùng cung cấp.
- **Kịch bản đã sử dụng:** [interview/guide-used.md](interview/guide-used.md), tóm tắt ở 3.2. Guide đề xuất cho lượt bổ sung ở 3.5 chưa được thực hiện.
- **Xin phép ghi âm:** Có; interviewer nói mục đích và không chia sẻ công khai, P01 trả lời “Ừm, đồng ý.”
- **Thời điểm bật ghi âm:** Chưa được xác nhận; chưa kiểm nghe âm thanh. Lời đồng ý trong transcript không tự xác định thời điểm bắt đầu ghi.
- **Thông tin bản ghi:** [interview/recording-link.md](interview/recording-link.md).

#### 4.4.2 Đối chiếu yêu cầu thực hành

| Yêu cầu CP3 | Trạng thái theo hồ sơ | Việc cần xác nhận / điều chỉnh |
| :--- | :--- | :--- |
| Ghép với người ngoài nhóm | Chưa có thông tin xác nhận | Người học xác nhận P01 có ngoài nhóm không |
| Không cho nhau xem solution directive | Chưa có thông tin xác nhận | Xác nhận việc không cho xem directive; không suy ra chỉ từ việc không đọc tên case |
| Đổi vai, mỗi người có một lượt interviewer | Hồ sơ này xác nhận một lượt interviewer; chưa biết lượt đổi vai | Xác nhận đã đổi vai; mỗi thành viên lưu riêng đúng lượt mình làm interviewer |
| Mỗi lượt interview 15 phút | Audio hiện có dài 05:29,6 | Xác nhận thời lượng toàn bộ lượt. Nếu đây là toàn bộ, hoạt động chưa đủ thời lượng đề yêu cầu |
| Xin phép trước khi ghi và nhận đồng ý | Có lời xin phép/đồng ý; thời điểm bật ghi chưa được xác nhận | Xác nhận thao tác bắt đầu ghi sau khi đồng ý |
| Follow câu chuyện, đào hành vi–workaround–hậu quả | Có mô tả cách xử lý chung, chưa neo một lần và kết quả cụ thể | Lượt bổ sung dùng câu neo sự kiện, hỏi từng hành động và kết quả; không ghi rằng đã làm việc này ở P01 |
| Không pitch solution, không hỏi muốn feature | **Chưa đạt trong nội dung lượt P01** | Câu “bạn có muốn là có được một cái công cụ như vậy không?” gợi solution. Giữ nguyên transcript và ghi nhận điểm cần sửa; không dùng lời đồng ý làm evidence |
| Hoàn thiện notes ở cuối hoạt động và quay lại nhóm | Notes hiện đã được tổng hợp; chưa biết thời điểm hoàn thiện/quay lại nhóm | Người học xác nhận diễn biến thực hành, không suy ra từ ngày sửa tệp |

#### 4.4.3 CHECKPOINT 3 — Practice completed

**Hồ sơ cho lượt cá nhân đã có ba thành phần cốt lõi:** một lượt làm interviewer, Interview Record và bản ghi có lời đồng ý của người tham gia trong transcript. Chất lượng evidence còn hạn chế; không coi mong muốn dùng công cụ là bằng chứng pain.

- [x] Có lượt hỏi của người làm interviewer trong transcript P01.
- [x] Có Interview Record theo đúng năm mục của đề.
- [x] Có recording.m4a và lời đồng ý ghi âm được ghi nhận trong transcript.
- [x] Phân biệt evidence với nguyện vọng/feature request; không dùng “muốn công cụ” để xác nhận pain.
- [ ] Xác nhận ghép người ngoài nhóm và không cho xem directive.
- [ ] Xác nhận lượt đổi vai và hồ sơ riêng của các thành viên khác, nếu có.
- [ ] Xác nhận thời lượng thực tế so với yêu cầu 15 phút/lượt.
- [ ] Xác nhận đã bắt đầu ghi sau khi người tham gia đồng ý.

**Kết luận hiện tại:** Hồ sơ lượt cá nhân đã được tổng hợp; chưa đủ thông tin để đánh dấu toàn bộ hoạt động CP3 của nhóm hoàn tất đúng quy trình. Các câu hỏi dẫn dắt và việc chưa dựng câu chuyện cụ thể cần được phản ánh trong Practice Reflection.

> Bản ghi chỉ dùng để xem lại, bóc transcript và phục vụ bài học; không chia sẻ công khai.

### 4.5 Đối chiếu bốn gate đánh giá

| Gate | Đánh giá theo hồ sơ hiện tại |
| :--- | :--- |
| 1. Problem Framing | Đã có chuỗi Solution → Change → Actor → Situation & Job → Pain → Evidence; A/B cụ thể và có điều kiện làm giả thuyết yếu đi. Chưa có đủ evidence xác nhận A/B, nhưng đây không phải điều kiện phải xác nhận ở CP1 |
| 2. Interview Design | Guide cuối ở 3.5 có Big 3, hỏi sự kiện quá khứ và không giới thiệu solution. Kịch bản thực tế được lưu riêng để review |
| 3. Interview Practice | Có bản ghi, Interview Record và lời đồng ý trong transcript. Còn hạn chế: chưa neo sự kiện, có câu gợi công cụ và chưa đào hành động–kết quả. Các thông tin quy trình chưa xác nhận nằm ở 4.4 |
| 4. Reflection & Revision | Đã ghi lỗi cụ thể và nối từng lỗi với sửa đổi trong guide. Người học cần rà soát reflection; việc chia sẻ và thống nhất guide chung của nhóm chưa được xác nhận |

### 4.6 Kiểm tra repo trước khi nộp

**Tên repo theo mẫu:** `Track1_Day17_2A202602855_DoTrongBinh`.

Thư mục workspace hiện có tên `Track1_Day17_2A202602855_DoTrongBinh` và đã có thư mục `.git`. Chưa kiểm tra tên repo trên nền tảng nộp hoặc quyền truy cập của giảng viên/TA.

```text
Track1_Day17_2A202602855_DoTrongBinh/
├── README.md
└── interview/
    ├── notes.md
    ├── recording.m4a
    ├── recording-link.md   # thông tin bản ghi cục bộ, không phải link thay thế
    ├── guide-used.md       # kịch bản thực tế, bổ sung để review
    └── transcript.md       # tài liệu bổ sung, không bắt buộc
```

- [x] README có đủ năm phần theo đề.
- [x] notes.md ghi đúng lượt cá nhân làm interviewer P01 và có bảng Interview Record.
- [x] Có recording.m4a trong interview; không cần thay bằng link Drive.
- [x] Transcript ghi nhận người tham gia đồng ý cho ghi âm.
- [x] Guide cuối đã được sửa từ lỗi trong buổi luyện; không làm lộ solution; giữ hành động và kết quả trong cùng mạch.
- [ ] Người học rà soát ba câu reflection và hoàn thiện phần tự kiểm tra trong AI Support Log.
- [ ] Xác nhận đã chia sẻ với nhóm và thống nhất Conversation Guide chung.
- [ ] Kiểm tra tên repo trên nền tảng nộp đúng mẫu và giảng viên/TA mở được README, notes và bản ghi; chỉ cấp quyền cho người được phép xem.

**Trạng thái CP4:** Đã chỉnh nội dung guide và reflection để có thể review. Chưa đánh dấu hoàn tất nộp bài vì chưa xác nhận bước trao đổi nhóm, rà soát cá nhân và quyền truy cập repo/bản ghi.

## 5. AI Support Log

- **AI đã giúp gì:** Soạn CP1–CP2 cho Case A theo directive nhóm cung cấp; sau khi nhận transcript P01, lưu nguồn nguyên văn, tổng hợp Interview Record, exact quotes, giới hạn evidence, cập nhật trạng thái phỏng vấn và ghi âm, thêm đánh giá sau phỏng vấn và chất liệu reflection. Khi nhận recording.m4a, cập nhật đường dẫn/thời lượng từ metadata, ghi lại kịch bản thực tế và chuyển guide đề xuất cho lượt sau sang 3.5. Đối chiếu CP3 với đề, thêm bảng Interview Record năm mục và trạng thái các yêu cầu; giữ các thông tin chưa xác nhận và chênh lệch thời lượng. Khi nhận đề CP4, soạn ba câu reflection từ transcript, ghi bảng sửa guide dựa trên lỗi cụ thể, sắp README thành năm phần và thêm bảng bốn gate/checklist nộp bài.
- **Điểm nào sai hoặc hời hợt:** Bản đầu dùng sai case minh họa. Bản hiện tại đã đúng Case A; tuy nhiên dữ liệu P01 chủ yếu là lời kể chung, có câu hỏi dẫn dắt, chưa có sự kiện riêng hoặc kết quả để xác nhận A/B. Không coi lời đồng ý muốn công cụ là evidence về pain/adoption.
- **AI đã rà soát gì:** Đối chiếu quotes với transcript; giữ A/B như giả thuyết trước phỏng vấn; thêm H3 về thời gian xử lý như hướng cần điều tra; ghi consent đúng lời đáp, xác nhận recording.m4a tồn tại và thời lượng 329,6 giây từ metadata; không suy đoán ngày phỏng vấn, trạng thái ngoài nhóm hay đổi vai. Chưa kiểm nghe từng câu audio–transcript. Thêm câu neo sự kiện cho guide, giữ hành động và kết quả trong cùng mạch.
- **Những chỉnh sửa bạn đã yêu cầu trong quá trình làm bài:** Xác nhận và yêu cầu sửa về Case A khi AI dùng sai case; yêu cầu câu hỏi không đưa hướng của nhóm, giữ lời mở đầu dài có xin phép ghi âm và gộp hành động với kết quả. Bạn cung cấp transcript/bản ghi để bản tổng hợp bám vào buổi thực tế.
- **Bạn đã tự kiểm tra bản cuối thế nào:** [Người học bổ sung sau khi đối chiếu reflection, notes và guide với trải nghiệm thật; chưa ghi nhận bước rà soát này đã hoàn tất.]
