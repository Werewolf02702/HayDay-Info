import React, { useState, useMemo } from 'react';
import { 
  Factory, 
  Search, 
  X, 
  Zap, 
  Star, 
  Gift, 
  Ghost,
  Bird,
  Waves,
  Beef,
  LayoutGrid,
  Clock,
  Package,
  Sprout,
  ArrowRight,
  TrendingUp,
  Apple,
  Coins,
  Palette,
  Sparkles
} from 'lucide-react';

const App = () => {
  const [activeTab, setActiveTab] = useState('productions'); // 'productions', 'animals', 'crops'
  const [selectedItem, setSelectedItem] = useState(null);
  const [searchTerm, setSearchTerm] = useState('');

  // Данные о продуктах и их рецептах
  const recipes = {
    'Хлеб': { 
      level: 2, 
      time: '5 мин', 
      masteryTime: '4 мин (3★)', 
      boost: '1💎',
      exp: 3,
      sellPrice: '21💰',
      ingredients: [{ name: 'Пшеница', amount: 3 }] 
    },
    'Кукурузный хлеб': { 
      level: 7, 
      time: '30 мин', 
      masteryTime: '25 мин (3★)', 
      boost: '3💎',
      exp: 8,
      sellPrice: '72💰',
      ingredients: [{ name: 'Кукуруза', amount: 2 }, { name: 'Яйцо', amount: 2 }] 
    },
    'Печенье': { 
      level: 10, 
      time: '1 час', 
      masteryTime: '51 мин (3★)', 
      boost: '4💎',
      exp: 13,
      sellPrice: '104💰',
      ingredients: [{ name: 'Пшеница', amount: 2 }, { name: 'Коричневый сахар', amount: 1 }, { name: 'Яйцо', amount: 2 }] 
    },
    'Кекс с малиной': { 
      level: 19, 
      time: '45 мин', 
      masteryTime: '38 мин (3★)', 
      boost: '3💎',
      exp: 17,
      sellPrice: '140💰',
      ingredients: [{ name: 'Малина', amount: 2 }, { name: 'Пшеница', amount: 2 }, { name: 'Яйцо', amount: 1 }] 
    },
    'Кекс с ежевикой': { 
      level: 26, 
      time: '45 мин', 
      masteryTime: '38 мин (3★)', 
      boost: '3💎',
      exp: 27,
      sellPrice: '226💰',
      ingredients: [{ name: 'Ежевика', amount: 2 }, { name: 'Пшеница', amount: 2 }, { name: 'Яйцо', amount: 1 }] 
    },
    'Пицца': { 
      level: 33, 
      time: '15 мин', 
      masteryTime: '12 мин (3★)', 
      boost: '2💎',
      exp: 23,
      sellPrice: '190💰',
      ingredients: [{ name: 'Пшеница', amount: 2 }, { name: 'Сыр', amount: 1 }, { name: 'Помидор', amount: 1 }] 
    },
    'Кекс с черникой': { 
      level: 33, 
      time: '45 мин', 
      masteryTime: '38 мин (3★)', 
      boost: '3💎',
      exp: 28,
      sellPrice: '230💰',
      ingredients: [{ name: 'Пшеница', amount: 1 }, { name: 'Яйцо', amount: 2 }, { name: 'Черника', amount: 2 }] 
    },
    'Острая пицца': { 
      level: 37, 
      time: '15 мин', 
      masteryTime: '12 мин (3★)', 
      boost: '2💎',
      exp: 27,
      sellPrice: '226💰',
      ingredients: [{ name: 'Пшеница', amount: 2 }, { name: 'Помидор', amount: 1 }, { name: 'Сыр', amount: 1 }, { name: 'Перец чили', amount: 1 }] 
    },
    'Гамбургер': { level: 18, time: '2 часа', ingredients: [{ name: 'Хлеб', amount: 2 }, { name: 'Бекон', amount: 2 }] },
    'Корм для кур': { level: 3, time: '5 мин', ingredients: [{ name: 'Пшеница', amount: 2 }, { name: 'Кукуруза', amount: 1 }] },
    'Корм для коров': { level: 6, time: '10 мин', ingredients: [{ name: 'Кукуруза', amount: 2 }, { name: 'Соя', amount: 1 }] },
  };

  const productions = [
    { 
      id: 'bakery', 
      name: 'Пекарня', 
      level: 2, 
      category: 'Базовая еда', 
      items: ['Хлеб', 'Кукурузный хлеб', 'Печенье', 'Кекс с малиной', 'Кекс с ежевикой', 'Пицца', 'Кекс с черникой', 'Острая пицца'],
      buildPrice: '20 монет',
      buildTime: '10 сек',
      buildExp: 3
    },
    { 
      id: 'grinder_1', 
      name: 'Дробилка (I)', 
      level: 3, 
      category: 'Переработка', 
      items: ['Корм для кур', 'Корм для коров'],
      buildPrice: '5 монет',
      buildTime: '40 сек',
      buildExp: 4
    },
    { 
      id: 'dairy', 
      name: 'Молокозавод', 
      level: 6, 
      category: 'Ингредиенты', 
      items: ['Сливки', 'Сливочное масло', 'Сыр'],
      buildPrice: '50 монет',
      buildTime: '2 часа',
      buildExp: 8
    },
    { 
      id: 'sugar_mill_1', 
      name: 'Сахарный завод (I)', 
      level: 7, 
      category: 'Ингредиенты', 
      items: ['Тростниковый сахар', 'Белый сахар'] 
    },
    { 
      id: 'popcorn', 
      name: 'Попкорница', 
      level: 8, 
      category: 'Закуски', 
      items: ['Обычный попкорн', 'Попкорн с маслом'] 
    },
    { 
      id: 'grill', 
      name: 'Гриль', 
      level: 9, 
      category: 'Базовая еда', 
      items: ['Блины', 'Яичница with беконом', 'Гамбургер'] 
    },
    { 
      id: 'grinder_2', 
      name: 'Дробилка (II)', 
      level: 12, 
      category: 'Переработка', 
      items: ['Корм для овец', 'Корм для свиней'],
      buildPrice: '3200 монет',
      buildTime: '40 сек',
      buildExp: 4
    },
    { id: 'pie_oven', name: 'Печь для пирогов', level: 14, category: 'Выпечка', items: ['Морковный пирог', 'Тыквенный пирог'] },
    { id: 'loom', name: 'Ткацкий станок', level: 17, category: 'Текстиль', items: ['Хлопковая ткань', 'Шерстяная ткань'] },
    { id: 'sewing', name: 'Швейная машина', level: 19, category: 'Текстиль', items: ['Рубашка', 'Шерстяные штаны'] },
    { id: 'cake_oven', name: 'Печь для тортов', level: 21, category: 'Выпечка', items: ['Морковный торт', 'Шоколадный торт'] },
    { id: 'smelter', name: 'Плавильня', level: 24, category: 'Металлы', items: ['Слиток железа', 'Слиток золота', 'Слиток меди'] },
    { id: 'juicer', name: 'Соковыжималка', level: 26, category: 'Напитки', items: ['Морковный сок', 'Яблочный сок'] },
    { id: 'ice_cream', name: 'Мороженица', level: 29, category: 'Сладости', items: ['Ванильное мороженое', 'Вишневое мороженое'] },
    { id: 'jam_maker', name: 'Вареньеварка', level: 35, category: 'Заготовки', items: ['Яблочное варенье', 'Малиновое варенье'] },
    { id: 'jeweler', name: 'Ювелир', level: 38, category: 'Металлы', items: ['Кольцо', 'Ожерелье', 'Браслет'] },
    { id: 'honey_extractor', name: 'Медогонка', level: 39, category: 'Ингредиенты', items: ['Мед', 'Воск'] },
  ];

  const animals = [
    { 
      id: 'chicken', name: 'Курица', level: 1, category: 'Животные', enclosures: [1, 12, 23], icon: 'bird',
      production: { item: 'Яйцо', amount: '1 шт', time: '20 мин' }
    },
    { 
      id: 'cow', name: 'Корова', level: 6, category: 'Животные', enclosures: [6, 15, 27], icon: 'beef',
      production: { item: 'Молоко', amount: '1 бидон', time: '1 час' }
    },
    { 
      id: 'pig', name: 'Свинья', level: 10, category: 'Животные', enclosures: [10, 18, 32], icon: 'beef',
      production: { item: 'Бекон', amount: '1 ед', time: '4 часа' }
    },
    { 
      id: 'sheep', name: 'Овца', level: 16, category: 'Животные', enclosures: [16, 26, 42], icon: 'beef',
      production: { item: 'Шерсть', amount: '1 ед', time: '6 часов' }
    },
    { 
      id: 'fish', name: 'Рыба', level: 27, category: 'Водные', enclosures: [], icon: 'waves',
      production: { item: 'Филе рыбы', amount: '1 или 3 шт', time: 'Мгновенно / 20-21ч', note: 'Зависит от способа (приманка/сеть)' }
    },
    { 
      id: 'goat', name: 'Коза', level: 32, category: 'Животные', enclosures: [32, 37, 50], icon: 'beef',
      production: { item: 'Козье молоко', amount: '1 бидон', time: '6 часов' }
    },
    { 
      id: 'bee', name: 'Пчела', level: 39, category: 'Насекомые', enclosures: [], icon: 'star',
      production: { item: 'Соты', amount: '1 ед (улей)', time: '30-35 мин', note: '1 капля нектара в мин на каждую пчелу (вместимость 100)' }
    },
  ];

  const crops = [
    { id: 'wheat', name: 'Пшеница', level: 1, category: 'Культуры', time: '2 мин', exp: 1, icon: 'sprout' },
    { id: 'corn', name: 'Кукуруза', level: 2, category: 'Культуры', time: '5 мин', exp: 1, icon: 'sprout' },
    { id: 'soy', name: 'Соя', level: 5, category: 'Культуры', time: '20 мин', exp: 2, icon: 'sprout' },
    { id: 'sugarcane', name: 'Сахарный тростник', level: 7, category: 'Культуры', time: '30 мин', exp: 3, icon: 'sprout' },
    { id: 'carrot', name: 'Морковь', level: 9, category: 'Культуры', time: '10 мин', exp: 2, icon: 'sprout' },
    { id: 'indigo', name: 'Индиго', level: 13, category: 'Культуры', time: '2 часа', exp: 5, icon: 'sprout' },
    { id: 'pumpkin', name: 'Тыква', level: 15, category: 'Культуры', time: '3 часа', exp: 6, icon: 'sprout' },
    { id: 'apple', name: 'Яблоко', level: 15, category: 'Деревья', time: '16 часов', exp: 7, icon: 'apple' },
    { id: 'cotton', name: 'Хлопок', level: 18, category: 'Культуры', time: '2ч 30мин', exp: 6, icon: 'sprout' },
    { id: 'raspberry', name: 'Малина', level: 19, category: 'Кусты', time: '18 часов', exp: 9, icon: 'sprout' },
    { id: 'cherry', name: 'Вишня', level: 22, category: 'Деревья', time: '1д 4ч', exp: 13, icon: 'apple' },
    { id: 'chili', name: 'Перец чили', level: 25, category: 'Культуры', time: '4ч', exp: 7, icon: 'sprout' },
    { id: 'blackbean', name: 'Черный боб', level: 25, category: 'Культуры', time: '10 мин', exp: 2, icon: 'sprout' },
    { id: 'blackberry', name: 'Ежевика', level: 26, category: 'Кусты', time: '1д 8ч', exp: 16, icon: 'sprout' },
    { id: 'tomato', name: 'Помидоры', level: 30, category: 'Культуры', time: '6ч', exp: 8, icon: 'sprout' },
    { id: 'blueberry', name: 'Черника', level: 30, category: 'Кусты', time: '1д 11ч', exp: 16, icon: 'sprout' },
    { id: 'strawberry', name: 'Клубника', level: 34, category: 'Культуры', time: '8ч', exp: 10, icon: 'sprout' },
    { id: 'potato', name: 'Картофель', level: 35, category: 'Культуры', time: '3ч 40мин', exp: 7, icon: 'sprout' },
    { id: 'cocoabean', name: 'Какао бобы', level: 36, category: 'Деревья', time: '1д 11ч', exp: 16, icon: 'apple' },
    { id: 'coffeebean', name: 'Кофейные зерна', level: 42, category: 'Кусты', time: '1д 1ч', exp: 12, icon: 'sprout' },
    { id: 'chamomile', name: 'Ромашка', level: 45, category: 'Цветы', time: '20 мин', exp: 2, icon: 'sprout' },
    { id: 'asparagus', name: 'Спаржа', level: 49, category: 'Культуры', time: '6ч', exp: 8, icon: 'sprout' },
    { id: 'sesame', name: 'Кунжут', level: 50, category: 'Культуры', time: '1ч', exp: 4, icon: 'sprout' },
    { id: 'pineapple', name: 'Ананас', level: 52, category: 'Культуры', time: '30 мин', exp: 3, icon: 'sprout' },
    { id: 'lily', name: 'Лилия', level: 53, category: 'Цветы', time: '1ч 30мин', exp: 5, icon: 'sprout' },
    { id: 'rice', name: 'Рис', level: 56, category: 'Культуры', time: '45 мин', exp: 3, icon: 'sprout' },
    { id: 'olives', name: 'Оливки', level: 57, category: 'Деревья', time: '1д', exp: 17, icon: 'apple' },
    { id: 'lettuce', name: 'Латук', level: 58, category: 'Культуры', time: '3ч 30мин', exp: 7, icon: 'sprout' },
    { id: 'garlic', name: 'Чеснок', level: 60, category: 'Культуры', time: '30 мин', exp: 3, icon: 'sprout' },
    { id: 'sunflower', name: 'Подсолнух', level: 63, category: 'Цветы', time: '1ч 30мин', exp: 5, icon: 'sprout' },
    { id: 'cabbage', name: 'Капуста', level: 65, category: 'Культуры', time: '45 мин', exp: 3, icon: 'sprout' },
    { id: 'lemon', name: 'Лимон', level: 66, category: 'Деревья', time: '1д 6ч', exp: 18, icon: 'apple' },
    { id: 'onion', name: 'Лук', level: 68, category: 'Культуры', time: '5ч', exp: 8, icon: 'sprout' },
    { id: 'cucumber', name: 'Огурец', level: 70, category: 'Культуры', time: '35 мин', exp: 3, icon: 'sprout' },
    { id: 'orange', name: 'Апельсин', level: 71, category: 'Деревья', time: '1д 7ч', exp: 19, icon: 'apple' },
    { id: 'beet', name: 'Свекла', level: 72, category: 'Культуры', time: '40 мин', exp: 3, icon: 'sprout' },
    { id: 'bellpepper', name: 'Болгарский перец', level: 74, category: 'Культуры', time: '4ч 30мин', exp: 7, icon: 'sprout' },
    { id: 'peach', name: 'Персик', level: 76, category: 'Деревья', time: '1д 6ч', exp: 20, icon: 'apple' },
    { id: 'ginger', name: 'Имбирь', level: 78, category: 'Культуры', time: '2ч 30мин', exp: 6, icon: 'sprout' },
    { id: 'tealeaves', name: 'Чайные листья', level: 80, category: 'Кусты', time: '6ч 30мин', exp: 9, icon: 'sprout' },
    { id: 'peony', name: 'Пион', level: 82, category: 'Цветы', time: '4ч', exp: 7, icon: 'sprout' },
    { id: 'broccoli', name: 'Брокколи', level: 83, category: 'Культуры', time: '1ч 20мин', exp: 4, icon: 'sprout' },
    { id: 'grapes', name: 'Виноград', level: 84, category: 'Кусты', time: '3ч', exp: 6, icon: 'sprout' },
    { id: 'mint', name: 'Мята', level: 85, category: 'Культуры', time: '3ч', exp: 6, icon: 'sprout' },
    { id: 'passionfruit', name: 'Маракуйя', level: 88, category: 'Кусты', time: '1ч', exp: 4, icon: 'sprout' },
    { id: 'banana', name: 'Банан', level: 88, category: 'Деревья', time: '1д 4ч', exp: 20, icon: 'apple' },
    { id: 'mushroom', name: 'Грибы', level: 89, category: 'Лес', time: '20 мин', exp: 2, icon: 'sprout' },
    { id: 'watermelon', name: 'Арбуз', level: 92, category: 'Культуры', time: '5ч', exp: 8, icon: 'sprout' },
    { id: 'clay', name: 'Глина', level: 94, category: 'Материалы', time: '1ч 50мин', exp: 5, icon: 'palette' },
    { id: 'plum', name: 'Слива', level: 94, category: 'Деревья', time: '1д 1ч', exp: 16, icon: 'apple' },
    { id: 'chickpea', name: 'Нут', level: 95, category: 'Культуры', time: '1ч', exp: 4, icon: 'sprout' },
    { id: 'mango', name: 'Манго', level: 97, category: 'Деревья', time: '1д 8ч', exp: 20, icon: 'apple' },
    { id: 'coconut', name: 'Кокос', level: 101, category: 'Деревья', time: '1д 12ч', exp: 21, icon: 'apple' },
    { id: 'guava', name: 'Гуава', level: 104, category: 'Деревья', time: '1д 10ч', exp: 22, icon: 'apple' },
    { id: 'pomegranate', name: 'Гранат', level: 107, category: 'Деревья', time: '1д 3ч', exp: 22, icon: 'apple' },
    { id: 'oats', name: 'Овес', level: 119, category: 'Культуры', time: '7 мин', exp: 1, icon: 'sprout' },
  ];

  // Умная фильтрация
  const filteredData = useMemo(() => {
    const s = searchTerm.toLowerCase();
    if (!s) return { productions, animals, crops };

    const matchesIngredients = (items) => {
      return items?.some(itemName => {
        const recipe = recipes[itemName];
        return recipe?.ingredients?.some(ing => ing.name.toLowerCase().includes(s));
      });
    };

    return {
      productions: productions.filter(p => 
        p.name.toLowerCase().includes(s) || 
        p.items.some(i => i.toLowerCase().includes(s)) ||
        matchesIngredients(p.items)
      ),
      animals: animals.filter(a => 
        a.name.toLowerCase().includes(s) || 
        a.production?.item.toLowerCase().includes(s)
      ),
      crops: crops.filter(c => c.name.toLowerCase().includes(s))
    };
  }, [searchTerm]);

  const currentList = useMemo(() => {
    if (activeTab === 'productions') return filteredData.productions;
    if (activeTab === 'animals') return filteredData.animals;
    return filteredData.crops;
  }, [activeTab, filteredData]);

  const levels = Array.from(new Set(currentList.map(item => item.level))).sort((a, b) => a - b);

  const getIcon = (item) => {
    if (item.icon === 'apple') return <Apple className="w-7 h-7 text-red-500" />;
    if (item.icon === 'palette') return <Palette className="w-7 h-7 text-amber-600" />;
    if (activeTab === 'crops' || item.icon === 'sprout') return <Sprout className="w-7 h-7 text-green-400" />;
    if (activeTab === 'animals') {
      if (item.icon === 'bird') return <Bird className="w-7 h-7 text-amber-400" />;
      if (item.icon === 'waves') return <Waves className="w-7 h-7 text-blue-400" />;
      return <Beef className="w-7 h-7 text-orange-400" />;
    }
    return <Factory className="w-7 h-7 text-slate-400 group-hover:text-cyan-400 transition-colors" />;
  };

  return (
    <div className="min-h-screen bg-slate-950 text-slate-100 p-4 md:p-10 font-sans selection:bg-cyan-500/30">
      <header className="max-w-5xl mx-auto mb-12 text-center">
        <h1 className="text-5xl md:text-6xl font-black mb-8 bg-gradient-to-b from-white to-slate-500 bg-clip-text text-transparent italic tracking-tighter uppercase">
          {activeTab === 'productions' ? 'Производство' : activeTab === 'animals' ? 'Животные' : 'Поля'}
        </h1>
        
        <div className="flex flex-col md:flex-row items-center gap-4 max-w-3xl mx-auto">
          <div className="relative flex-1 w-full">
            <Search className="absolute left-4 top-1/2 -translate-y-1/2 w-5 h-5 text-slate-500" />
            <input 
              type="text" 
              placeholder="Поиск здания или ингредиента..." 
              className="w-full bg-slate-900/50 border border-slate-800 rounded-2xl py-4 pl-12 pr-4 focus:outline-none focus:ring-2 focus:ring-cyan-500/50 transition-all backdrop-blur-md"
              value={searchTerm}
              onChange={(e) => setSearchTerm(e.target.value)}
            />
          </div>
          <div className="flex bg-slate-900/80 p-1.5 rounded-2xl border border-slate-800 w-full md:w-auto overflow-x-auto">
            <button onClick={() => setActiveTab('productions')} className={`flex-1 px-4 py-2.5 rounded-xl text-[10px] font-black transition-all whitespace-nowrap ${activeTab === 'productions' ? 'bg-cyan-500 text-slate-950 shadow-lg shadow-cyan-500/20' : 'text-slate-400 hover:text-white'}`}>ЗДАНИЯ</button>
            <button onClick={() => setActiveTab('animals')} className={`flex-1 px-4 py-2.5 rounded-xl text-[10px] font-black transition-all whitespace-nowrap ${activeTab === 'animals' ? 'bg-orange-500 text-slate-950 shadow-lg shadow-orange-500/20' : 'text-slate-400 hover:text-white'}`}>ЖИВОТНЫЕ</button>
            <button onClick={() => setActiveTab('crops')} className={`flex-1 px-4 py-2.5 rounded-xl text-[10px] font-black transition-all whitespace-nowrap ${activeTab === 'crops' ? 'bg-green-500 text-slate-950 shadow-lg shadow-green-500/20' : 'text-slate-400 hover:text-white'}`}>КУЛЬТУРЫ</button>
          </div>
        </div>
      </header>

      <div className="max-w-4xl mx-auto">
        {levels.map((level) => (
          <div key={level} className="mb-12">
            <div className="flex items-center gap-4 mb-6">
              <div className="h-px flex-1 bg-slate-800" />
              <div className="px-4 py-1 rounded-full bg-slate-900 border border-slate-700 text-xs font-bold text-slate-500 uppercase tracking-tighter italic">Уровень {level}</div>
              <div className="h-px flex-1 bg-slate-800" />
            </div>
            <div className="grid grid-cols-1 sm:grid-cols-2 gap-4">
              {currentList.filter(i => i.level === level).map((item) => (
                <button key={item.id} onClick={() => setSelectedItem(item)} className="group p-4 bg-slate-900/40 border border-slate-800 rounded-2xl hover:bg-slate-800/60 transition-all flex items-center gap-4 backdrop-blur-sm relative overflow-hidden text-left">
                  {item.isNew && (
                    <div className="absolute top-2 right-2 flex items-center gap-1 bg-cyan-500 text-slate-950 px-2 py-0.5 rounded-full text-[8px] font-black animate-pulse">
                      <Sparkles className="w-2 h-2" />
                      NEW
                    </div>
                  )}
                  <div className="w-12 h-12 rounded-xl bg-slate-800 flex items-center justify-center group-hover:scale-110 transition-transform">{getIcon(item)}</div>
                  <div className="text-left">
                    <h3 className="font-bold text-white group-hover:text-cyan-400 transition-colors">{item.name}</h3>
                    <p className="text-[10px] text-slate-500 uppercase font-black tracking-widest">{item.category}</p>
                  </div>
                </button>
              ))}
            </div>
          </div>
        ))}
      </div>

      {selectedItem && (
        <div className="fixed inset-0 z-[100] flex items-center justify-center p-4 backdrop-blur-md bg-slate-950/80">
          <div className="relative w-full max-w-md bg-slate-900 border border-slate-700 rounded-[2.5rem] overflow-hidden animate-in zoom-in-95 shadow-2xl">
            <div className={`p-8 pb-4 flex justify-between items-start ${activeTab === 'crops' ? 'bg-green-500/5' : activeTab === 'animals' ? 'bg-orange-500/5' : 'bg-cyan-500/5'}`}>
              <div>
                <p className={`text-[10px] font-black uppercase mb-1 ${activeTab === 'crops' ? 'text-green-500' : activeTab === 'animals' ? 'text-orange-500' : 'text-cyan-500'}`}>Уровень {selectedItem.level}</p>
                <div className="flex items-center gap-3">
                  <h2 className="text-3xl font-black text-white">{selectedItem.name}</h2>
                  {selectedItem.isNew && (
                    <span className="bg-cyan-500 text-slate-950 text-[10px] px-2 py-1 rounded-lg font-black italic">NEW</span>
                  )}
                </div>
              </div>
              <button onClick={() => setSelectedItem(null)} className="p-2 text-slate-500 hover:text-white transition-colors"><X /></button>
            </div>

            <div className="p-8 pt-4 space-y-4">
              {/* Строительная информация для зданий */}
              {selectedItem.buildPrice && (
                <div className="grid grid-cols-3 gap-2 mb-2">
                  <div className="bg-slate-950/50 p-3 rounded-2xl border border-slate-800">
                    <Coins className="text-yellow-500 w-4 h-4 mb-1" />
                    <p className="text-[8px] text-slate-500 font-bold uppercase">Цена</p>
                    <p className="text-xs font-bold text-white">{selectedItem.buildPrice}</p>
                  </div>
                  <div className="bg-slate-950/50 p-3 rounded-2xl border border-slate-800">
                    <Clock className="text-blue-400 w-4 h-4 mb-1" />
                    <p className="text-[8px] text-slate-500 font-bold uppercase">Сборка</p>
                    <p className="text-xs font-bold text-white">{selectedItem.buildTime || '—'}</p>
                  </div>
                  <div className="bg-slate-950/50 p-3 rounded-2xl border border-slate-800">
                    <TrendingUp className="text-purple-400 w-4 h-4 mb-1" />
                    <p className="text-[8px] text-slate-500 font-bold uppercase">Опыт</p>
                    <p className="text-xs font-bold text-white">+{selectedItem.buildExp || '0'}</p>
                  </div>
                </div>
              )}

              {/* Информация для культур или деревьев */}
              {(activeTab === 'crops' || (activeTab !== 'productions' && selectedItem.time)) && (
                <div className="grid grid-cols-2 gap-3">
                  <div className="bg-slate-950/50 p-5 rounded-3xl border border-green-500/10">
                    <Clock className="text-green-400 w-4 h-4 mb-2" />
                    <p className="text-[9px] text-slate-500 font-bold uppercase mb-1">Время</p>
                    <p className="text-lg font-bold text-white">{selectedItem.time}</p>
                  </div>
                  <div className="bg-slate-950/50 p-5 rounded-3xl border border-amber-500/10">
                    <TrendingUp className="text-amber-400 w-4 h-4 mb-2" />
                    <p className="text-[9px] text-slate-500 font-bold uppercase mb-1">Опыт (XP)</p>
                    <p className="text-lg font-bold text-white">+{selectedItem.exp} XP</p>
                  </div>
                </div>
              )}

              {/* Информация для животных */}
              {activeTab === 'animals' && selectedItem.production && (
                <div className="bg-slate-950/50 p-6 rounded-3xl border border-orange-500/20 space-y-4">
                  <div className="flex items-center gap-4">
                    <Package className="text-orange-400 w-5 h-5" />
                    <div>
                      <p className="text-[10px] text-slate-500 font-bold uppercase">Продукт</p>
                      <p className="font-bold text-white">{selectedItem.production.amount} {selectedItem.production.item}</p>
                    </div>
                  </div>
                  <div className="flex items-center gap-4">
                    <Clock className="text-orange-400 w-5 h-5" />
                    <div>
                      <p className="text-[10px] text-slate-500 font-bold uppercase">Время</p>
                      <p className="font-bold text-white">{selectedItem.production.time}</p>
                    </div>
                  </div>
                </div>
              )}

              {/* Продукция и рецепты зданий */}
              {activeTab === 'productions' && selectedItem.items && (
                <div className="space-y-4 max-h-[40vh] overflow-y-auto pr-2 custom-scrollbar">
                  {selectedItem.items.map(itemName => {
                    const recipe = recipes[itemName];
                    return (
                      <div key={itemName} className="bg-slate-950/50 p-5 rounded-3xl border border-slate-800 hover:border-slate-600 transition-colors">
                        <div className="flex justify-between items-center mb-3">
                          <h4 className="font-black text-white uppercase tracking-tighter">{itemName}</h4>
                          {recipe && (
                            <div className="flex flex-col items-end">
                              <span className="text-[10px] font-bold text-slate-300 uppercase tracking-widest">{recipe.time}</span>
                              {recipe.masteryTime && <span className="text-[8px] font-black text-cyan-400">{recipe.masteryTime}</span>}
                            </div>
                          )}
                        </div>
                        
                        {recipe && (
                          <div className="grid grid-cols-2 gap-2 mb-4">
                            <div className="flex items-center gap-2 bg-slate-900/80 p-2 rounded-xl border border-slate-800">
                              <Zap className="w-3 h-3 text-cyan-400" />
                              <span className="text-[10px] font-bold text-white uppercase">{recipe.boost}</span>
                            </div>
                            <div className="flex items-center gap-2 bg-slate-900/80 p-2 rounded-xl border border-slate-800">
                              <Coins className="w-3 h-3 text-yellow-500" />
                              <span className="text-[10px] font-bold text-white uppercase">{recipe.sellPrice}</span>
                            </div>
                          </div>
                        )}

                        {recipe?.ingredients && (
                          <div className="space-y-2 border-t border-slate-800 pt-3">
                            <div className="flex justify-between items-center">
                              <p className="text-[9px] text-slate-500 font-black uppercase italic">Ингредиенты:</p>
                              {recipe.exp && <span className="text-[9px] font-black text-purple-400 uppercase">+{recipe.exp} XP</span>}
                            </div>
                            {recipe.ingredients.map(ing => (
                              <div key={ing.name} className="flex items-center justify-between text-sm">
                                <span className="text-slate-400">{ing.name}</span>
                                <span className="font-bold text-cyan-500">x{ing.amount}</span>
                              </div>
                            ))}
                          </div>
                        )}
                      </div>
                    );
                  })}
                </div>
              )}
            </div>
          </div>
        </div>
      )}
    </div>
  );
};

export default App;

