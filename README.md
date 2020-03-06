# int value = rnd.Next(0,2);
            int k = 0;
            string[] name = new string[10] { "гироскутер", "ноутбук", "велосипед", "ролексы", "AirPods", "гантели", "пистолет", "деньги", "статуэтка", "телевизор" };
            int weight1 = 6;
            int weight2 = 3;
            int weight3 = 7;
            int weight4 = 2;
            int weight5 = 1;
            int weight6 = 14;
            int weight7 = 2;
            int weight8 = 3;
            int weight9 = 4;
            int weight10 = 5;
            int[] price = new int[10] { 500, 3000, 170, 24000, 900, 80, 800, 4500, 410, 633 };
            int max_weight = 19;
            string[,] mass = new string[100, 10];
            for(int i = 0; i<= 100; i++)
            {
                for (int j = 0; j <= 10; j++)
                {
                    if (max_weight - weight1 >= 0)
                    {
                        mass[k, 0] = name[0];
                        max_weight = max_weight - weight1;
                        if(max_weight - weight2 >= 0)
                        {

                        }
                        }
                    else
                    {
                        if(max_weight - weight2 >= 0)
                        {
                            mass[k, 0] = name[1];
                            max_weight = max_weight - weight2;
                            if(max_weight - weight3 >= 0)
                            {
                                mass[k, 1] = name[2];
                                max_weight = max_weight - weight3;

                            }
                        }
                    }
                        if(value == 1 & max_weight - weight2 >= 0)
                        {
                            mass[k, 1] = name[1];
                            max_weight = max_weight - weight2;
                            if(value == 1 & max_weight - weight3 >= 0)
                            {
                                mass[k, 2] = name[1];
                                max_weight = max_weight - weight2;
                                if(value == 1 & max_weight - weight3 >= 0)
                                {
                                    mass[k, 3] = name[1];
                                    max_weight = max_weight - weight2;
                                }
                            }
                        }
                    }
                    if(mass[i,j] == mass[i,j])
                    {
                        Console.WriteLine(mass[i, j]);
                    }
