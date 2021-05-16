{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf610
{\fonttbl\f0\froman\fcharset0 Times-Roman;}
{\colortbl;\red255\green255\blue255;\red49\green50\blue61;\red255\green255\blue255;\red29\green38\blue43;
\red247\green247\blue247;\red228\green240\blue231;}
{\*\expandedcolortbl;;\cssrgb\c25098\c25882\c30588;\cssrgb\c100000\c100000\c100000;\cssrgb\c15294\c19608\c22353;
\cssrgb\c97647\c97647\c97647;\cssrgb\c91373\c95294\c92549;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\b\fs29\fsmilli14667 \cf2 \cb3 \expnd0\expndtw0\kerning0
pyqrcode
\fs34  module
\b0  is a QR code generator. The module automates most of the building process for creating QR codes. This module attempts to follow the QR code standard as closely as possible. The terminology and the encodings used in 
\fs29\fsmilli14667 pyqrcode 
\fs34 come directly from the standard.\cb1 \

\b \cb3 Installation
\b0 \cb1 \
\pard\pardeftab720\partightenfactor0

\fs32 \cf4 \cb5 $ pip install pyqrcode\
\pard\pardeftab720\partightenfactor0

\fs34 \cf2 \cb3 \'a0\cb1 \
\cb3 install an additional module pypng to save image in png format:\cb1 \
\pard\pardeftab720\partightenfactor0

\fs32 \cf4 \cb5 $ pip install pypng\
\pard\pardeftab720\partightenfactor0

\fs34 \cf2 \cb3 \'a0\cb1 \

\b\fs29\fsmilli14667 \cb3 pyqrcode.create(content, error='H', version=None, mode=None, encoding=None)
\fs34  :
\b0  When creating a QR code only the content to be encoded is required, all the other properties of the code will be guessed based on the contents given. This function will return a 
\fs29\fsmilli14667 QRCode 
\fs34 object\
\
One can specify all the properties of required QR code through the optional parameters of the 
\fs29\fsmilli14667 pyqrcode.create()
\fs34  function. Below are some properties:\cb1 \
\pard\pardeftab720\partightenfactor0

\b \cf2 \cb6 error:
\b0  This parameter sets the error correction level of the code.\cb1 \

\b \cb6 version:
\b0  This parameter specifies the size and data capacity of the code.\cb1 \

\b \cb6 mode:
\b0  This parameter sets how the contents will be encoded}