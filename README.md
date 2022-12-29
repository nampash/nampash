        public static void Zachet() // Метод в QuickStart
        {
            Double f;
            if (!(Input("a", out double a)))
                return;
            if (a<=0)
            {
                f =0;
            }
            else 
            { 
                if(a > 1)
                {
                    f = Math.Sqrt(a);
                }
                else
                {
                    f = Math.Sqrt(a) - Math.Sin(Math.PI*a);
                }
            }
            Console.WriteLine("Значение f: " + f);
        }
