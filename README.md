# _Drupal Shift Cipher_

##### _Encodes user inputted string using a shift cipher, 10/23/15_

#### By _**Jordan J. Johansen**_

## Description

_Clicking on the "Shift Cipher" link in the navigation menu takes the user to a page containing a form with three input fields: one asks the user to input a string of text to encode, one asks the user which direction they want to shift the string (left or right), and the last asks how many places they want to shift each letter in the string.  The "Phrase" field is validated to ensure that the user has inputted a valid string, i.e. one containing only letters, spaces, or certain allowed punctuation.  The "Shift Value" field is validated to ensure that the inputted number is both a positive integer, and that said integer is greater than 0 and less than 26 (as both of these values would result in the encoded string being the same as the inputted string).  The "Shift Direction" field is validated to ensure that the user has entered only "left" or "right".  All input fields trim trailing whitespace.  When the user clicks "Encode", they are taken to another page where the newly encoded string is displayed._

## Setup
* _Clone the repository from GitHub._

* On Mac:
Set the MAMP root directory to the project folder.  Navigate to MAMP's phpMyAdmin page and import the database zip file found in sites/db\_backup. (jordanj\_cipher.sql.zip)

* _After selecting the newly imported database, click on the "Privileges" tab and add create a user with these settings:<br>
User Name: admin<br>
host: localhost<br>
Password: epicodus_

* _On Windows:
Do the same as above, but through WAMP, or whatever server you're using._

* _Open your browser and go to localhost:8888._

* _Database Information:_<br>
Database name: jordanj\_cipher<br>
_Database user: admin_<br>
_Password: epicodus_

* _Site admin account information_<br>
_Admin user: admin_<br>
_Password: epicodus_

## Technologies Used
_Drupal 7.41_

## Legal

Copyright (c) 2015 Jordan J. Johansen

This software is licensed under the MIT license.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
