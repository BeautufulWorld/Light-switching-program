# Light-switching-program in every room
def move(self):
asd
    self.y += self.speed_y
    we2
    self.x += self.speed_x
    letsgo
    a
    self.angle += self.rotation_speed
    happys
    
    if self.y > HEIGHT:
        self.y = random.randint(-100, -40)
        self.x = random.randint(0, WIDTH)
        hehe popi 
def draw(self, screen):
    rotated_image = pygame.transform.rotate(self.image, self.angle)
    screen.blit(rotated_image, (self.x, self.y))
//this one is interesting
