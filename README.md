Chatbot:
Chatbot là một ứng dụng Streamlit tương tác với Chatbot của Hugging Face. Người dùng có thể nhập thông tin đăng nhập tài khoản Hugging Face vào thanh bên để bắt đầu.
Cách sử dụng:
Nhập email và mật khẩu tài khoản Hugging Face của bạn vào thanh bên.
Bắt đầu trò chuyện với chatbot trong giao diện chính.
Cách hoạt động:
Ứng dụng khởi tạo với thông điệp trợ lý ban đầu: “Làm ơn cho tôi biết bạn cần giúp đỡ về điều gì?”
Tin nhắn của người dùng được lưu trữ trong trạng thái phiên.
Hàm generate_response đăng nhập vào Hugging Face bằng thông tin đăng nhập được cung cấp, tạo một phiên bản chatbot và trò chuyện với chatbot.
Nếu người dùng nhập tin nhắn mới, nó sẽ được thêm vào trạng thái phiên.
Nếu tin nhắn cuối cùng không phải từ trợ lý, bạn sẽ tạo phản hồi bằng cách sử dụng hàm generate_response.

Word Correction using Levenshtein Distance:
Ứng dụng này sử dụng thuật toán khoảng cách Levenshtein để sửa lỗi chính tả trong từ vựng. Bạn nhập một từ và ứng dụng sẽ gợi ý từ gần đúng nhất.
Cách sử dụng:
Nhập từ cần kiểm tra vào ô “Word”.
Nhấn nút “Compute” để tính toán.
Cách hoạt động:
Ứng dụng tính khoảng cách Levenshtein giữa từ bạn nhập và từ trong từ điển.
Từ gần đúng nhất sẽ được hiển thị.
Yêu cầu:
Python 3.6+
Streamlit
