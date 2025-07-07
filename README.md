# Django Installation


1. ตรวจสอบว่ามีการติดตั้ง Python แล้วในเครื่อง

**Windows & MacOS**
```
- Open the Command Prompt / Terminal
- Enter the command
> py --version
```

**Results**
```
> python --version
Python 3.9.13
```

2. สร้าง folder สำหรับใส่ project เช่น `My Documents\Projects\week-2`

3. เข้าไปที่ folder

4. Setup a virtual environment

**Windows**
```
# Install virtualenv
> pip install virtualenv

# Create a virtual environment
> py -m venv myvenv

# Activate virtual environment
> myvenv\Scripts\activate.bat
```

**MacOS**
```
# Install virtualenv
> pip install virtualenv

# Create a virtual environment
> python -m venv myvenv

# Activate virtual environment
> source myvenv/bin/activate
```

เมื่อทำเสร็จคุณจะเห็นว่ามี folder `myvenv` เพิ่มขึ้นมา

5. Install Django

**Windows & MacOS**

```
> pip install django
```

ตรวจสอบว่า install สำเร็จหรือไม่ด้วย command

```
> python -m django --version
4.2.13
```

6. Add `path` to `psql` ใน Windows environment variables

6.1 ไปที่ folder ที่มีไฟล์ `pgAdmin4.exe`

6.2 Copy path ที่อยู่ของไฟล์ `psql.exe` เพื่อนำไป add ใน `path`

6.3 เพิ่ม `path` to `psql` ใน Windows environment variables

![Screenshot 2025-07-07 153642](https://github.com/user-attachments/assets/0dd77e8b-8e9e-46a3-a471-0fc614aa0646)

7. 

เราจะมาสร้าง project Django กันต่อ ตามขั้นตอนในไฟล์ `tutorial.md`
