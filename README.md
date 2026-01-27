# Blood Donor Management System

A comprehensive C-based console application for managing blood donors and blood bank operations. This system provides a complete solution for blood banks to manage donor information, track blood stock, and serve blood to customers.

## 🩸 Features

### Blood Donor Management System
- **Add Donor**: Register new blood donors with complete information
- **Delete Donor**: Remove donors from the system using contact number
- **Edit Donor**: Update donor information (address and last donation date)
- **Search Donor**: Find donors by blood group and address
- **Filter Donor**: View donors who donated blood less than 3 months ago
- **View All Donors**: Display complete list of registered donors
- **Data Persistence**: Save and load donor data from files

### Blood Bank Management System
- **Add Blood Stock**: Manage blood inventory by blood group
- **Serve Blood**: Process blood requests from customers
- **View Blood Stock**: Display current blood inventory levels
- **View Customer List**: Track all blood service transactions
- **Admin Authentication**: Secure access with password protection
- **Data Management**: Persistent storage of stock and customer data

## 📋 Prerequisites

- C compiler (GCC recommended)
- Windows/Linux/macOS operating system
- Basic understanding of console applications

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/BloodDonorManagement.git
   cd BloodDonorManagement
   ```

2. **Compile the program**
   ```bash
   gcc -o main Main.c
   ```

3. **Run the application**
   ```bash
   ./main
   ```
   On Windows:
   ```bash
   main.exe
   ```

## 📖 Usage Guide

### Main Menu
The application starts with a main menu offering four options:
1. **Blood Donor Management System**
2. **Blood Bank Management System**
3. **Help**
4. **About**

### Blood Donor Management

#### Adding a Donor
1. Select option 1 from main menu
2. Choose option 1 (Add Donor)
3. Enter donor details:
   - Name
   - Contact Number
   - Address
   - Blood Group
   - Last Donation Date (YYYY-MM-DD format)
4. Save to file using option 6

#### Managing Donors
- **Delete**: Use contact number to remove donors
- **Edit**: Update address and donation date by contact number
- **Search**: Find donors by blood group and address
- **Filter**: View eligible donors (donated >3 months ago)

### Blood Bank Management

#### Access Control
- **Password**: `admin123` (default admin password)
- **Security**: Password-protected access to blood bank operations

#### Blood Stock Management
- **Add Stock**: Increase blood inventory by blood group
- **View Stock**: Check current blood availability
- **Serve Blood**: Process customer requests and update inventory

#### Customer Service
- **Serve Blood**: Record blood service transactions
- **View Customers**: Track all blood service history

## 📁 File Structure

```
BloodDonorManagement/
├── Main.c                 # Main source code
├── main.exe              # Compiled executable (Windows)
├── donors.txt            # Donor database
├── blood_stock.txt       # Blood inventory data
├── customer_list.txt     # Customer transaction records
├── README.md            # This file
└── blood_donor.pptx     # Project presentation
```

## 💾 Data Storage

The system uses simple text files for data persistence:

- **donors.txt**: Stores donor information (CSV format)
- **blood_stock.txt**: Tracks blood inventory by group
- **customer_list.txt**: Records blood service transactions

### Data Format Examples

**Donor Record:**
```
Name,ContactNumber,Address,BloodGroup,LastDonationDate
```

**Blood Stock:**
```
BloodGroup Quantity
```

**Customer Transaction:**
```
Name,ContactNumber,Address,BloodGroup,Bags,Date
```

## 🔧 Technical Details

- **Language**: C
- **Data Structures**: Linked Lists
- **File I/O**: Text file operations
- **Memory Management**: Dynamic allocation with proper cleanup
- **Platform**: Cross-platform (Windows/Linux/macOS)

## 🛡️ Security Features

- **Admin Authentication**: Password-protected blood bank access
- **Data Validation**: Input validation for critical operations
- **Memory Safety**: Proper memory allocation and deallocation

## 📊 System Requirements

- **RAM**: Minimum 512MB
- **Storage**: 10MB free space
- **OS**: Windows 10+, Linux, macOS
- **Compiler**: GCC or compatible C compiler

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Sowjanya** - *Initial work* - [YourGitHubUsername](https://github.com/SOWJANYAKAGITHA)

## 🙏 Acknowledgments

- Blood bank management concepts
- C programming best practices
- Console application design patterns

## 📞 Support

For support and questions:
- Create an issue in the GitHub repository
- Contact the project maintainer
- Check the Help section in the application

---

**Note**: This system is designed for educational and demonstration purposes. For production use in actual blood banks, additional security measures and compliance with healthcare regulations would be required. 
