<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>Gửi cô giáo Đặng Thanh Nhàn</title>
  <link rel="stylesheet" href="style.css">

</head>
<body>

    <!-- partial:index.partial.html -->
    <h1>Gửi cô giáo Đặng Thanh Nhàn</h1>

    <div class="container">
    <div class="card-carousel">
        <div class="card" id="1">
        <div class="image-container"></div>
        <p>Nhân ngày Phụ nữ Việt Nam, em chúc cô luôn mạnh khỏe, hạnh phúc và thành công trong sự nghiệp trồng người.</p>
        </div>
        <div class="card" id="2">
        <div class="image-container"></div>
        <p>Em xin gửi lời chúc 20/10 dành tặng cô giáo, thêm nhiều hạnh phúc thêm nhiều sức khỏe. Cô là người mẹ thứ 2 trong cuộc đời em.</p>
        </div>
        <div class="card" id="3">
        <div class="image-container"></div>
        <p>Lời chúc 20/10 dành tặng cô giáo không bao giờ là đủ, mỗi lời chúc như một đóa hoa tặng tới cô. Em xin chúc cô luôn tươi trẻ như những đóa hoa đó. Mong cô mãi mãi khỏe mạnh và hạnh phúc.</p>
        </div>  
        <div class="card" id="4">
        <div class="image-container"></div>
        <p>Có một nghề bụi phấn bám đầy tay
            Người ta bảo đó là nghề trong sạch nhất
            Có một nghề không trồng cây vào đất
            Mà mang lại cho đời đầy "trái ngọt hoa tươi""</p>
        </div>
        <div class="card" id="5">
        <div class="image-container"></div>
        <p> Em xin chúc cô luôn tràn ngập niềm vui, đầy nhiệt huyết với sự nghiệp nhà giáo của mình. Chúc cô có sức khỏe thật tốt để vững bước chèo lái “con thuyền trồng người” giúp chúng em đến bến bờ thành công.</p>
        </div>
    </div>
    <a href="#" class="visuallyhidden card-controller">Carousel controller</a>
    </div>
    <!-- partial -->
    <script  src="script.js"></script>
    <style>
        * {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  font-family: system-ui;
  background: #3d76d9;
}

.visuallyhidden {
  position: absolute;
  z-index: -1;
  right: 0;
  opacity: 0;
  
}

h1 {
  color: white;
  text-align: center;
  margin-top: 1em;
}

.container {
  overflow: hidden;
  padding: 20px;
  margin-top: 2em;
  background: rgba(0,0,0,.1)
}

.card-carousel {
  --card-width: 80%;
  --card-max-width: 280px;
  --card-height: 350px;
  --carousel-min-width: 600px;
  z-index: 1;
  position: relative;
  margin: 0 auto;
  width: 100%;
  height: var(--card-height);
  min-width: var(--carousel-min-width);
  transition: filter .3s ease;
}

@media screen and (max-width: 640px) {
  .card-carousel {
    margin-left: calc((100vw - var(--carousel-min-width) - 40px) / 2)
  }
}

.card-carousel.smooth-return {
  transition: all .2s ease;
}

.card-carousel .card {
  background: whitesmoke;
  width: var(--card-width);
  max-width: var(--card-max-width);
  text-align: center;
  padding: 1em;
  min-width: 250px;
  height: var(--card-height);
  position: absolute;
  margin: 0 auto;
  color: rgba(0,0,0,.5);
  transition: inherit;
  -webkit-box-shadow: 0px 5px 5px 0px rgba(0,0,0,0.3);
  -moz-box-shadow: 0px 5px 5px 0px rgba(0,0,0,0.3);
  box-shadow: 0px 5px 5px 0px rgba(0,0,0,0.3);
  border-radius: 1em;
  filter: brightness(.9);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.card.highlight {
  filter: brightness(1)
}


.card:nth-of-type(1) .image-container {
    background-image: url("https://scontent.fhph1-1.fna.fbcdn.net/v/t1.15752-9/247538254_931817064092991_9052135297235670997_n.jpg?_nc_cat=104&ccb=1-5&_nc_sid=ae9488&_nc_ohc=pMZewZHxDrIAX86xBaJ&tn=cDVQIAIYpAmOlgUs&_nc_ht=scontent.fhph1-1.fna&oh=88879ef3b7cdae3ebb2b4d75fc17bdd4&oe=6196CFA8");
}
 
.card:nth-of-type(2) .image-container {
  background-image: url("https://scontent.fhph1-2.fna.fbcdn.net/v/t1.15752-9/243426473_1158442627897524_5242235881497373356_n.jpg?_nc_cat=101&ccb=1-5&_nc_sid=ae9488&_nc_ohc=Ez9LP6FdRJ8AX_7Uafh&_nc_ht=scontent.fhph1-2.fna&oh=c53b080d59d5e95cf75d1db851130b8d&oe=619629BE")
}

.card:nth-of-type(3) .image-container {
  background-image: url("https://scontent-sin6-4.xx.fbcdn.net/v/t1.15752-9/245669419_409068750832331_5279138848130356668_n.jpg?_nc_cat=103&ccb=1-5&_nc_sid=ae9488&_nc_ohc=Bw4wSQ-YpMYAX8RlDk3&_nc_ht=scontent-sin6-4.xx&oh=80dfe23ed84842dd625bebecf45e47b4&oe=61967840")
}
.card:nth-of-type(4) .image-container {
  background-image: url("https://scontent.fhph2-1.fna.fbcdn.net/v/t1.15752-9/245416168_1842856699219274_2404642221088512240_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=ae9488&_nc_ohc=XqE6rOGtvrIAX-_rhpZ&_nc_ht=scontent.fhph2-1.fna&oh=3da5409af1392f4fe435a382830391e3&oe=617156CF")
}
.card:nth-of-type(5) .image-container {
  background-image: url("https://scontent-sin6-3.xx.fbcdn.net/v/t1.15752-9/246430750_3028255930777944_5750051604496110634_n.jpg?_nc_cat=110&ccb=1-5&_nc_sid=ae9488&_nc_ohc=FeHJESnSYGEAX_h6KG_&_nc_ht=scontent-sin6-3.xx&oh=74558f0a0d90acfb2d105b3ec1715e2f&oe=6171328F")
}



.image-container {
  width: 8em;
  height: 8em;
  position: relative;
  background-size: cover;
  margin-bottom: 2em;
  border-radius: 100%;
  padding: 1em;
  -webkit-box-shadow: inset 0px 0px 17px 0px rgba(0,0,0,0.3);
-moz-box-shadow: inset 0px 0px 17px 0px rgba(0,0,0,0.3);
box-shadow: inset 0px 0px 17px 0px rgba(0,0,0,0.3);
  
}

.image-container::after {
  content: "";
  display: block;
  width: 120%;
  height: 120%;
  border: solid 3px rgba(0,0,0,.1);
  border-radius: 100%;
  position: absolute;
  top: calc(-10% - 3px);
  left: calc(-10% - 3px);
}
    </style>
    <script language="javascript">
        const cardsContainer = document.querySelector(".card-carousel");
const cardsController = document.querySelector(".card-carousel + .card-controller")

class DraggingEvent {
  constructor(target = undefined) {
    this.target = target;
  }
  
  event(callback) {
    let handler;
    
    this.target.addEventListener("mousedown", e => {
      e.preventDefault()
      
      handler = callback(e)
      
      window.addEventListener("mousemove", handler)
      
      document.addEventListener("mouseleave", clearDraggingEvent)
      
      window.addEventListener("mouseup", clearDraggingEvent)
      
      function clearDraggingEvent() {
        window.removeEventListener("mousemove", handler)
        window.removeEventListener("mouseup", clearDraggingEvent)
      
        document.removeEventListener("mouseleave", clearDraggingEvent)
        
        handler(null)
      }
    })
    
    this.target.addEventListener("touchstart", e => {
      handler = callback(e)
      
      window.addEventListener("touchmove", handler)
      
      window.addEventListener("touchend", clearDraggingEvent)
      
      document.body.addEventListener("mouseleave", clearDraggingEvent)
      
      function clearDraggingEvent() {
        window.removeEventListener("touchmove", handler)
        window.removeEventListener("touchend", clearDraggingEvent)
        
        handler(null)
      }
    })
  }
  
  // Get the distance that the user has dragged
  getDistance(callback) {
    function distanceInit(e1) {
      let startingX, startingY;
      
      if ("touches" in e1) {
        startingX = e1.touches[0].clientX
        startingY = e1.touches[0].clientY
      } else {
        startingX = e1.clientX
        startingY = e1.clientY
      }
      

      return function(e2) {
        if (e2 === null) {
          return callback(null)
        } else {
          
          if ("touches" in e2) {
            return callback({
              x: e2.touches[0].clientX - startingX,
              y: e2.touches[0].clientY - startingY
            })
          } else {
            return callback({
              x: e2.clientX - startingX,
              y: e2.clientY - startingY
            })
          }
        }
      }
    }
    
    this.event(distanceInit)
  }
}


class CardCarousel extends DraggingEvent {
  constructor(container, controller = undefined) {
    super(container)
    
    // DOM elements
    this.container = container
    this.controllerElement = controller
    this.cards = container.querySelectorAll(".card")
    
    // Carousel data
    this.centerIndex = (this.cards.length - 1) / 2;
    this.cardWidth = this.cards[0].offsetWidth / this.container.offsetWidth * 100
    this.xScale = {};
    
    // Resizing
    window.addEventListener("resize", this.updateCardWidth.bind(this))
    
    if (this.controllerElement) {
      this.controllerElement.addEventListener("keydown", this.controller.bind(this))      
    }

    
    // Initializers
    this.build()
    
    // Bind dragging event
    super.getDistance(this.moveCards.bind(this))
  }
  
  updateCardWidth() {
    this.cardWidth = this.cards[0].offsetWidth / this.container.offsetWidth * 100
    
    this.build()
  }
  
  build(fix = 0) {
    for (let i = 0; i < this.cards.length; i++) {
      const x = i - this.centerIndex;
      const scale = this.calcScale(x)
      const scale2 = this.calcScale2(x)
      const zIndex = -(Math.abs(i - this.centerIndex))
      
      const leftPos = this.calcPos(x, scale2)
     
      
      this.xScale[x] = this.cards[i]
      
      this.updateCards(this.cards[i], {
        x: x,
        scale: scale,
        leftPos: leftPos,
        zIndex: zIndex
      })
    }
  }
  
  
  controller(e) {
    const temp = {...this.xScale};
      
      if (e.keyCode === 39) {
        // Left arrow
        for (let x in this.xScale) {
          const newX = (parseInt(x) - 1 < -this.centerIndex) ? this.centerIndex : parseInt(x) - 1;

          temp[newX] = this.xScale[x]
        }
      }
      
      if (e.keyCode == 37) {
        // Right arrow
        for (let x in this.xScale) {
          const newX = (parseInt(x) + 1 > this.centerIndex) ? -this.centerIndex : parseInt(x) + 1;

          temp[newX] = this.xScale[x]
        }
      }
      
      this.xScale = temp;
      
      for (let x in temp) {
        const scale = this.calcScale(x),
              scale2 = this.calcScale2(x),
              leftPos = this.calcPos(x, scale2),
              zIndex = -Math.abs(x)

        this.updateCards(this.xScale[x], {
          x: x,
          scale: scale,
          leftPos: leftPos,
          zIndex: zIndex
        })
      }
  }
  
  calcPos(x, scale) {
    let formula;
    
    if (x < 0) {
      formula = (scale * 100 - this.cardWidth) / 2
      
      return formula

    } else if (x > 0) {
      formula = 100 - (scale * 100 + this.cardWidth) / 2
      
      return formula
    } else {
      formula = 100 - (scale * 100 + this.cardWidth) / 2
      
      return formula
    }
  }
  
  updateCards(card, data) {
    if (data.x || data.x == 0) {
      card.setAttribute("data-x", data.x)
    }
    
    if (data.scale || data.scale == 0) {
      card.style.transform = `scale(${data.scale})`

      if (data.scale == 0) {
        card.style.opacity = data.scale
      } else {
        card.style.opacity = 1;
      }
    }
   
    if (data.leftPos) {
      card.style.left = `${data.leftPos}%`        
    }
    
    if (data.zIndex || data.zIndex == 0) {
      if (data.zIndex == 0) {
        card.classList.add("highlight")
      } else {
        card.classList.remove("highlight")
      }
      
      card.style.zIndex = data.zIndex  
    }
  }
  
  calcScale2(x) {
    let formula;
   
    if (x <= 0) {
      formula = 1 - -1 / 5 * x
      
      return formula
    } else if (x > 0) {
      formula = 1 - 1 / 5 * x
      
      return formula
    }
  }
  
  calcScale(x) {
    const formula = 1 - 1 / 5 * Math.pow(x, 2)
    
    if (formula <= 0) {
      return 0 
    } else {
      return formula      
    }
  }
  
  checkOrdering(card, x, xDist) {    
    const original = parseInt(card.dataset.x)
    const rounded = Math.round(xDist)
    let newX = x
    
    if (x !== x + rounded) {
      if (x + rounded > original) {
        if (x + rounded > this.centerIndex) {
          
          newX = ((x + rounded - 1) - this.centerIndex) - rounded + -this.centerIndex
        }
      } else if (x + rounded < original) {
        if (x + rounded < -this.centerIndex) {
          
          newX = ((x + rounded + 1) + this.centerIndex) - rounded + this.centerIndex
        }
      }
      
      this.xScale[newX + rounded] = card;
    }
    
    const temp = -Math.abs(newX + rounded)
    
    this.updateCards(card, {zIndex: temp})

    return newX;
  }
  
  moveCards(data) {
    let xDist;
    
    if (data != null) {
      this.container.classList.remove("smooth-return")
      xDist = data.x / 250;
    } else {

      
      this.container.classList.add("smooth-return")
      xDist = 0;

      for (let x in this.xScale) {
        this.updateCards(this.xScale[x], {
          x: x,
          zIndex: Math.abs(Math.abs(x) - this.centerIndex)
        })
      }
    }

    for (let i = 0; i < this.cards.length; i++) {
      const x = this.checkOrdering(this.cards[i], parseInt(this.cards[i].dataset.x), xDist),
            scale = this.calcScale(x + xDist),
            scale2 = this.calcScale2(x + xDist),
            leftPos = this.calcPos(x + xDist, scale2)
      
      
      this.updateCards(this.cards[i], {
        scale: scale,
        leftPos: leftPos
      })
    }
  }
}

const carousel = new CardCarousel(cardsContainer)
    </script>
</body>
</html>
