//                                                                                                               //
//              This program written for SOURCE and HSID board of IONICAXX to                                    //
//              control the HV and Temperature of HSID and Source                                                //
//              MehrdadT@ionics.ca         Date : Aug 12th, 2008       				    						 //	
//              Version : 2.0 based on dsPIC33  							    								 //	
//              comment: this version has a PID control parameter to control temperature with seperate           //                                                                                                 //
//              latest update for Source May12 was regarding immidiate heater shut down after zero set point     //
//              latest update for HV+ and HV- seperate setting                                                   // 
//              HSID heat controller fixed   July30th 2009                                                       // 
//              Calibration fixed Aug5th 2009                                                                    //
//              Fuzzy control start Aug 26th and finished successfull on Aug 28th                                //  
//              Change and mod for HV monitor and Temperature reading also temp control on Jan13,2010            //
//              Open loop temp control Jan13,2010                                                                //   
//              The SPI will be reset if the instruction in serial communication isn't right(1,2,3,11,12)        //  
//              The SPI communication modified for fast respond to polling FEB15th,2010                          //   
//              SPI polling modified to Interrupt and works perfect Feb21,2010                                   //
//              CurtainCap logic changed (never disable curtaincap on APCI or ESI) Mar23                         //   
//              New PID temperature control May 20th 2010                                                        //                        
//              New PID optimizing Feb 17th, 2011  