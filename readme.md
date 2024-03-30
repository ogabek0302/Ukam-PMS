# Production Management System for Wildberries and Ozon

## About the Project

This software has been developed to optimize production management processes associated with operations on the Wildberries and Ozon platforms. The project's goal is to replace the use of various unrelated programs and Excel for production management, significantly improving work efficiency and facilitating more effective interaction between different departments and external suppliers.

## Key Features

- **Interaction with Suppliers via QR Codes**: Simplifies the ordering and receiving process of goods through the use of QR codes.
- **Integration with Wildberries and Ozon Platforms**: Convenient management of orders, products, and logistics from a single interface.
- **Barcode Generation for Packaging**: Automates the creation and printing of barcodes for packaging materials.
- **Product Management**: Complete control over the assortment, availability, and movement of goods.
- **XML Reporting for Tax Purposes**: Simplifies tax reporting through automatic generation of reports in the required format.
- **Management of Counterparties and Organizations**: Centralized management of all process participants.
- **Employee Rights Management System**: Assignment and control of access to various program functions for different categories of employees.
- **Editing and Printing Hardware Requests**: Optimizes the hardware ordering process with the ability to edit and print requests.
- **Documentation Error Checking**: Automatic checking of internal documents and counterpart documentation for errors.
- **Settings**: Flexible program configuration to match the specificities of the enterprise's operations.
- **Secure System Logout**: Ensures confidentiality of information through secure logout from the system.

## Technologies

This project is built using a wide range of technologies and libraries, focusing on PyQt5 for the graphical user interface and various other tools for handling data processing, file management, notifications, and more. Below is a detailed list of the components used:

### Main Technologies

- **PyQt5**: Used extensively for creating the GUI, including widgets like `QApplication`, `QMainWindow`, `QWidget`, `QVBoxLayout`, `QPushButton`, `QLabel`, `QTextEdit`, `QLineEdit`, `QTableWidget`, `QHeaderView`, `QHBoxLayout`, `QGridLayout`, `QFrame`, `QToolBar`, `QStackedWidget`, `QSizePolicy`, `QDialog`, `QPlainTextEdit`, `QCheckBox`, `QFormLayout`, `QDialogButtonBox`, `QErrorMessage`, `QFileDialog`, `QComboBox`, `QAbstractItemView`, `QGroupBox`, `QInputDialog`, `QMessageBox`, `QListWidget`, `QDateEdit`, `QProgressBar`, `QTabWidget`, `QCompleter`, `QScrollArea`, `QAction`, `QSystemTrayIcon`, and `QMenu`.
- **PyQt5.QtPrintSupport**: For printing capabilities, including `QPrinter` and `QPrintDialog`.
- **PyQt5.QtMultimedia**: Utilized for playing sounds via `QSound`.
- **PyQt5.QtGui**: For graphical elements such as `QImage`, `QPixmap`, `QPen`, `QIcon`, `QFont`, `QPainter`, and handling colors with `QColor`.
- **PyQt5.QtCore**: Core functionalities like `QDate`, `QThread`, `Qt`, `QSize`, `pyqtSignal`, `QRectF`, `QTimer`, `QSizeF`.

### Data Processing and File Management

- **OpenPyXL**: For creating and managing Excel files (`Workbook`, `load_workbook`).
- **Pandas**: Essential for data manipulation and analysis.
- **SQLite3**: Used for database management.
- **XML.etree.ElementTree** (ET): For XML file parsing and management.
- **JSON**: Handling JSON data.
- **re (Regular Expressions)**: For pattern matching and text manipulation.
- **os**: For interacting with the operating system and file management.
- **lxml.etree**: Another tool for XML parsing, offering more advanced capabilities compared to the standard ElementTree.

### Notifications and Graphics

- **Plyer**: For sending desktop notifications.
- **QtAwesome (qta)**: Provides FontAwesome icons for PyQt applications.
- **QRCode**: Generating QR codes for various uses within the application.
- **Barcode**: Generating barcodes (`Code128`, `EAN13`) with an `ImageWriter`.
- **PIL (Python Imaging Library)**: For image processing.
- **ReportLab**: For PDF generation and handling, with features like custom pagesizes (`letter`), colors, units (`mm`), and drawing on canvas.

### Miscellaneous

- **Qt Material**: To apply material design styles to PyQt applications.
- **Collections**: Utilized `defaultdict` for more efficient data management.
- **Random**: For generating random numbers.
- **DateTime**: Handling dates and times.
- **Time**: For time-based operations.
- **Typing**: To provide type hints and improve code readability.

This diverse set of technologies ensures that the system is robust, scalable, and capable of meeting the complex requirements of managing production processes for platforms like Wildberries and Ozon.

contacts to get demo version:
gmail: ogobekodilbek@gmail.com
telgramm: https://t.me/ukam_admin