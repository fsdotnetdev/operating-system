# Chapter 02

## Topic
* Store Data in Disk
* Printer
* System Call

## Store Data in Disk
* Disk
* track
* Sector
* Size
* Space Available

## Printer

## Program on Bare Hardware

## System Call
การเข้าถึง Instruction จะเข้าถึงได้ 2 โหมด คือ Kermel Mode จะเข้าถึงได้ทุก Instruction จะทำโดย Hardware แต่เวลาเราเขียนโปรแกรมจะเข้าถึง Instruction ผ่าน User Mode โดย OS จะมีส่วนที่ติดต่อ Instruction แทนเรียกว่า System Call


ในการเขียนโปรแกรม การจะเข้าถึง Instruction จะไม่สามารถเข้าถึงได้โดยตรงใน User Mode เพราะ OS จะไม่ยอมแต่จะให้ User Program เรียกใช้ Instruction ผ่าน Library ของ System Call ในภาษา Assembly

## Credit
Operatin System (6th Edition)
