<?xml version="1.0" encoding="utf-8"?>
<wsdl:definitions xmlns:soap="http://schemas.xmlsoap.org/wsdl/soap/" xmlns:tm="http://microsoft.com/wsdl/mime/textMatching/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:mime="http://schemas.xmlsoap.org/wsdl/mime/" xmlns:tns="http://www.alientech.to/" xmlns:s="http://www.w3.org/2001/XMLSchema" xmlns:soap12="http://schemas.xmlsoap.org/wsdl/soap12/" xmlns:http="http://schemas.xmlsoap.org/wsdl/http/" targetNamespace="http://www.alientech.to/" xmlns:wsdl="http://schemas.xmlsoap.org/wsdl/">
  <wsdl:types>
    <s:schema elementFormDefault="qualified" targetNamespace="http://www.alientech.to/">
      <s:element name="getinfofilelength">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="0" maxOccurs="1" name="id_sn" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="cat_prd" type="s:string" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="getinfofilelengthResponse">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="1" maxOccurs="1" name="getinfofilelengthResult" type="s:long" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="getupdinfo">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="0" maxOccurs="1" name="id_sn" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="cat_prd" type="s:string" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="getupdinfoResponse">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="0" maxOccurs="1" name="getupdinfoResult" type="s:base64Binary" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="getfile">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="0" maxOccurs="1" name="sezione" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="nomefile" type="s:string" />
            <s:element minOccurs="1" maxOccurs="1" name="lunghezzaSegmento" type="s:int" />
            <s:element minOccurs="1" maxOccurs="1" name="offsetSegmento" type="s:int" />
            <s:element minOccurs="0" maxOccurs="1" name="md5" type="s:string" />
            <s:element minOccurs="1" maxOccurs="1" name="lunghezzafile" type="s:int" />
            <s:element minOccurs="0" maxOccurs="1" name="id_sn" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="cat_prd" type="s:string" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="getfileResponse">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="0" maxOccurs="1" name="getfileResult" type="s:base64Binary" />
            <s:element minOccurs="0" maxOccurs="1" name="md5" type="s:string" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="sendverinfo">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="0" maxOccurs="1" name="id_sn" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="versioninfo" type="s:string" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="sendverinfoResponse">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="1" maxOccurs="1" name="sendverinfoResult" type="s:int" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="sendlog">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="0" maxOccurs="1" name="id_sn" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="prd" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="log_code" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="note" type="s:string" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="sendlogResponse">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="1" maxOccurs="1" name="sendlogResult" type="s:int" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="usr_registered">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="0" maxOccurs="1" name="id_sn" type="s:string" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="usr_registeredResponse">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="1" maxOccurs="1" name="usr_registeredResult" type="s:int" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="reguser">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="0" maxOccurs="1" name="id_sn" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="nome" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="email" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="telefono" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="cellulare" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="fax" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="indirizzo_primario" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="indirizzo_secondario" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="cap" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="city" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="provincia" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="nazione" type="s:string" />
            <s:element minOccurs="0" maxOccurs="1" name="lingua" type="s:string" />
            <s:element minOccurs="1" maxOccurs="1" name="mailing_list" type="s:int" />
          </s:sequence>
        </s:complexType>
      </s:element>
      <s:element name="reguserResponse">
        <s:complexType>
          <s:sequence>
            <s:element minOccurs="1" maxOccurs="1" name="reguserResult" type="s:int" />
          </s:sequence>
        </s:complexType>
      </s:element>
    </s:schema>
  </wsdl:types>
  <wsdl:message name="getinfofilelengthSoapIn">
    <wsdl:part name="parameters" element="tns:getinfofilelength" />
  </wsdl:message>
  <wsdl:message name="getinfofilelengthSoapOut">
    <wsdl:part name="parameters" element="tns:getinfofilelengthResponse" />
  </wsdl:message>
  <wsdl:message name="getupdinfoSoapIn">
    <wsdl:part name="parameters" element="tns:getupdinfo" />
  </wsdl:message>
  <wsdl:message name="getupdinfoSoapOut">
    <wsdl:part name="parameters" element="tns:getupdinfoResponse" />
  </wsdl:message>
  <wsdl:message name="getfileSoapIn">
    <wsdl:part name="parameters" element="tns:getfile" />
  </wsdl:message>
  <wsdl:message name="getfileSoapOut">
    <wsdl:part name="parameters" element="tns:getfileResponse" />
  </wsdl:message>
  <wsdl:message name="sendverinfoSoapIn">
    <wsdl:part name="parameters" element="tns:sendverinfo" />
  </wsdl:message>
  <wsdl:message name="sendverinfoSoapOut">
    <wsdl:part name="parameters" element="tns:sendverinfoResponse" />
  </wsdl:message>
  <wsdl:message name="sendlogSoapIn">
    <wsdl:part name="parameters" element="tns:sendlog" />
  </wsdl:message>
  <wsdl:message name="sendlogSoapOut">
    <wsdl:part name="parameters" element="tns:sendlogResponse" />
  </wsdl:message>
  <wsdl:message name="usr_registeredSoapIn">
    <wsdl:part name="parameters" element="tns:usr_registered" />
  </wsdl:message>
  <wsdl:message name="usr_registeredSoapOut">
    <wsdl:part name="parameters" element="tns:usr_registeredResponse" />
  </wsdl:message>
  <wsdl:message name="reguserSoapIn">
    <wsdl:part name="parameters" element="tns:reguser" />
  </wsdl:message>
  <wsdl:message name="reguserSoapOut">
    <wsdl:part name="parameters" element="tns:reguserResponse" />
  </wsdl:message>
  <wsdl:portType name="updateSoap">
    <wsdl:operation name="getinfofilelength">
      <wsdl:input message="tns:getinfofilelengthSoapIn" />
      <wsdl:output message="tns:getinfofilelengthSoapOut" />
    </wsdl:operation>
    <wsdl:operation name="getupdinfo">
      <wsdl:input message="tns:getupdinfoSoapIn" />
      <wsdl:output message="tns:getupdinfoSoapOut" />
    </wsdl:operation>
    <wsdl:operation name="getfile">
      <wsdl:input message="tns:getfileSoapIn" />
      <wsdl:output message="tns:getfileSoapOut" />
    </wsdl:operation>
    <wsdl:operation name="sendverinfo">
      <wsdl:input message="tns:sendverinfoSoapIn" />
      <wsdl:output message="tns:sendverinfoSoapOut" />
    </wsdl:operation>
    <wsdl:operation name="sendlog">
      <wsdl:input message="tns:sendlogSoapIn" />
      <wsdl:output message="tns:sendlogSoapOut" />
    </wsdl:operation>
    <wsdl:operation name="usr_registered">
      <wsdl:input message="tns:usr_registeredSoapIn" />
      <wsdl:output message="tns:usr_registeredSoapOut" />
    </wsdl:operation>
    <wsdl:operation name="reguser">
      <wsdl:input message="tns:reguserSoapIn" />
      <wsdl:output message="tns:reguserSoapOut" />
    </wsdl:operation>
  </wsdl:portType>
  <wsdl:binding name="updateSoap" type="tns:updateSoap">
    <soap:binding transport="http://schemas.xmlsoap.org/soap/http" />
    <wsdl:operation name="getinfofilelength">
      <soap:operation soapAction="http://www.alientech.to/getinfofilelength" style="document" />
      <wsdl:input>
        <soap:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
    <wsdl:operation name="getupdinfo">
      <soap:operation soapAction="http://www.alientech.to/getupdinfo" style="document" />
      <wsdl:input>
        <soap:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
    <wsdl:operation name="getfile">
      <soap:operation soapAction="http://www.alientech.to/getfile" style="document" />
      <wsdl:input>
        <soap:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
    <wsdl:operation name="sendverinfo">
      <soap:operation soapAction="http://www.alientech.to/sendverinfo" style="document" />
      <wsdl:input>
        <soap:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
    <wsdl:operation name="sendlog">
      <soap:operation soapAction="http://www.alientech.to/sendlog" style="document" />
      <wsdl:input>
        <soap:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
    <wsdl:operation name="usr_registered">
      <soap:operation soapAction="http://www.alientech.to/usr_registered" style="document" />
      <wsdl:input>
        <soap:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
    <wsdl:operation name="reguser">
      <soap:operation soapAction="http://www.alientech.to/reguser" style="document" />
      <wsdl:input>
        <soap:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
  </wsdl:binding>
  <wsdl:binding name="updateSoap12" type="tns:updateSoap">
    <soap12:binding transport="http://schemas.xmlsoap.org/soap/http" />
    <wsdl:operation name="getinfofilelength">
      <soap12:operation soapAction="http://www.alientech.to/getinfofilelength" style="document" />
      <wsdl:input>
        <soap12:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap12:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
    <wsdl:operation name="getupdinfo">
      <soap12:operation soapAction="http://www.alientech.to/getupdinfo" style="document" />
      <wsdl:input>
        <soap12:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap12:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
    <wsdl:operation name="getfile">
      <soap12:operation soapAction="http://www.alientech.to/getfile" style="document" />
      <wsdl:input>
        <soap12:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap12:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
    <wsdl:operation name="sendverinfo">
      <soap12:operation soapAction="http://www.alientech.to/sendverinfo" style="document" />
      <wsdl:input>
        <soap12:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap12:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
    <wsdl:operation name="sendlog">
      <soap12:operation soapAction="http://www.alientech.to/sendlog" style="document" />
      <wsdl:input>
        <soap12:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap12:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
    <wsdl:operation name="usr_registered">
      <soap12:operation soapAction="http://www.alientech.to/usr_registered" style="document" />
      <wsdl:input>
        <soap12:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap12:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
    <wsdl:operation name="reguser">
      <soap12:operation soapAction="http://www.alientech.to/reguser" style="document" />
      <wsdl:input>
        <soap12:body use="literal" />
      </wsdl:input>
      <wsdl:output>
        <soap12:body use="literal" />
      </wsdl:output>
    </wsdl:operation>
  </wsdl:binding>
  <wsdl:service name="update">
    <wsdl:port name="updateSoap" binding="tns:updateSoap">
      <soap:address location="http://13092011.com/update/update.asmx" />
    </wsdl:port>
    <wsdl:port name="updateSoap12" binding="tns:updateSoap12">
      <soap12:address location="http://13092011.com/update/update.asmx" />
    </wsdl:port>
  </wsdl:service>
</wsdl:definitions>
