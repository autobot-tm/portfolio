# Project Structure

### `src/app`

Chứa các thành phần chính của ứng dụng như cấu hình, nhà cung cấp (providers), bộ định tuyến (routers), và cửa hàng (stores).

- **`providers`**: Cung cấp các nhà cung cấp chính cho ứng dụng, ví dụ như Redux Provider.
- **`routers`**: Định nghĩa các tuyến đường của ứng dụng.
- **`stores`**: Cấu hình và kết hợp các reducer của Redux.

### `src/entities`

Chứa các thành phần, logic, và trạng thái liên quan đến các thực thể cụ thể trong ứng dụng.

### `src/pages`

Chứa các trang của ứng dụng, mỗi trang có thể có các thành phần, logic, và trạng thái riêng.

### `src/shared`

Chứa các thành phần, logic, và tiện ích dùng chung trong toàn bộ ứng dụng.

- **`ui`**: Chứa các thành phần giao diện người dùng dùng chung như `HatchButton`, `Modal`.
- **`lib`**: Chứa các hàm tiện ích dùng chung như `useDebounce`.
- **`assets`**: Chứa các tài nguyên như hình ảnh, âm thanh.

### `src`

Chứa các tệp cấu hình và khởi tạo ứng dụng.

- **`main.tsx`**: Điểm khởi đầu của ứng dụng, nơi ReactDOM.render được gọi.
- **`vite-env.d.ts`**: Tệp cấu hình môi trường cho Vite.

## Feature Sliced Design (FSD)

Feature Sliced Design là một phương pháp tổ chức mã nguồn theo tính năng, giúp dễ dàng quản lý và mở rộng. Các thư mục được tổ chức theo tính năng, mỗi tính năng có thể chứa các thành phần, logic, và trạng thái riêng.
