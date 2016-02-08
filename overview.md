/login
	POST
	RETURNS: a new user session
	FORMAT { 
		email: 'johndoe@gmail.com',
		password: '8WAtp8nUEOrzSu67t9tGITEzIdgr6huIpXqofo0rv2w9y3DzSu67t9tGITEzIdgr6huIpXqoTzARKuumMLuyHlGrWvGXy8acawjyliExMCHCfRU9VzlAipW4HFMVN3XZixDAw4EcmBHnnJozJYoPgheWYx3P1S11TEADaLlKVO5bXyBhEPQu6Z4jdUAdnHUkRuKBuHoCcU0hMTIhTzyYriExMCEI84A='
	}


/users/:id
	GET
	RETURNS: a user profile
	FORMAT: {
		id: 1,
		first_name: 'John',
		last_name: 'Doe'
		email: 'johndoe@gmail.com',
		gender: 'Male',
		address: '4299 Eglinton Avenue, Toronto, ON M4P 1A6',
		bio: 'SEO Expert. Amateur rugby player.',
		time_zone: 'UTC+12:00',
		photo: 'https://i.imgur.com/csCOvHj.jpg',
		landlord: false
	}

	/property/:id
		GET
		RETURNS: a property
		format: {
			home_type: 'House',
			capacity: 3,
			address: '4299 Eglinton Avenue, Toronto, ON M4P 1A6',
			bedrooms: 3,
			beds: 4,
			bathrooms: 2,
			title: 'Private Cozy Apt. in Tokyo',
			summary: 'It takes 5 min walk to Fujimidai Sta.. You can get on SeibIkebukuro Line, Subway Yuurakucho Line and Subway Fukutoshin Line. Ikebukuro 15 min, Ginza, Shinjuku and Shibuya within 30 min without having to transfer.',
			safety: {
				fire_alarm: true,
				fire_extinguisher: false,
				locked_safe: true
			},
			amenities: {
				wifi: true,
				air_con: true,
				heating: true, 
				washer: false,
				tv: false,
				parking: false,
				pets: true,
				smoking: false,
				wheelchair_accesible: true
			},
			photos: {
				image: ''
			}
		}