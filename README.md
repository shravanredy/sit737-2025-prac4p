# sit737-2025-prac4p

- REST API for **4 arithmetic operations**:
  - Addition
  - Subtraction
  - Multiplication
  - Division
  
- Validates inputs and handles errors gracefully
- Uses Winston to log:
  - All incoming requests
  - Operation results
  - Invalid inputs and errors
- Logs are saved to:
  - `logs/combined.log`
  - `logs/error.log`

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/sit737-2025-prac4p.git
cd sit737-2025-prac4p

To execute
npm install

To create logs directory
mkdir logs

Run the Microservice
node index.js
