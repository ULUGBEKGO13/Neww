# 
string[] name = new string[10] { "гироскутер", "ноутбук", "велосипед", "ролексы", "AirPods", "гантели", "пистолет", "деньги", "статуэтка", "телевизор" };
            int[] weight = new int[10] { 6, 3, 7, 2, 1, 14, 2, 3, 4, 5 };
            int[] price = new int[10] { 500, 3000, 170, 24000, 900, 80, 800, 4500, 410, 633 };
            int max_weight = 19;
            string Value = "";
            for(int i1 = 0; i1<= 2; i1++)
            {
                for (int i2 = 0; i2 <= 2; i2++)
                {
                    for (int i3 = 0; i3 <= 2; i3++)
                    {
                        for(int i4 = 0; i4 <= 2; i4++)
                        {
                            for(int i5 = 0; i5 <= 2; i5++)
                            {
                                for(int i6 = 0; i6 <= 2; i6++)
                                {
                                    for(int i7 = 0; i7 <= 2; i7++)
                                    {
                                        for(int i8 = 0; i8 <= 2; i8++)
                                        {
                                            for(int i9 = 0; i9 <= 2; i9++)
                                            {
                                                for(int i10 = 0; i10 <=2; i10++)
                                                {
                                                    for (int j = 0; j < 10; j++)
                                                    {
                                                        if (i1 == 1)
                                                        {
                                                            max_weight = max_weight - weight[0];
                                                            Value = Value + name[0];                                                           
                                                        }
                                                        if (i2 == 1)
                                                        {
                                                            max_weight = max_weight - weight[1];
                                                            Value = Value + name[1];                                                            
                                                        }
                                                        if (i3 == 1)
                                                        {
                                                            max_weight = max_weight - weight[2];
                                                            Value = Value + name[2];
                                                            Console.WriteLine(Value);
                                                        }
                                                        if (i4 == 1)
                                                        {
                                                            max_weight = max_weight - weight[3];
                                                            Value = Value + name[3];                                                           
                                                        }
                                                        if (i5 == 1)
                                                        {
                                                            max_weight = max_weight - weight[4];
                                                            Value = Value + name[4];                                                            
                                                        }
                                                        if (i6 == 1)
                                                        {
                                                            max_weight = max_weight - weight[5];
                                                            Value = Value + name[5];                                                            
                                                        }
                                                        if (i7 == 1)
                                                        {
                                                            max_weight = max_weight - weight[6];
                                                            Value = Value + name[6];                                                           
                                                        }
                                                        if (i8 == 1)
                                                        {
                                                            max_weight = max_weight - weight[7];
                                                            Value = Value + name[7];                                                            
                                                        }
                                                        if (i9 == 1)
                                                        {
                                                            max_weight = max_weight - weight[8];
                                                            Value = Value + name[8];
                                                        }
                                                        if (i10 == 1)
                                                        {
                                                            max_weight = max_weight - + weight[9];
                                                            Value = Value + name[9];
                                                        }
                                                        if (max_weight >= 0)
                                                        {
                                                            Console.WriteLine(i1 + " " + i2 + " " + i3 + " " + i4 + " " + i5 + " " + i6 + " " + i7 + "" + i8 + "" + i9 + "" + i10);
                                                        }
                                                    }
                                                }
                                            }
                                        }
                                    }
                                }
                            }
                        }
                    }
                }
            }
            Console.ReadKey();
